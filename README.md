# JSON Schema for SD-JWT Photo ID verifiable credential

This repository provides a JSON Schema implementation for the SD-JWT format, based on the [ISO/IEC TS 23220-4](https://www.iso.org/standard/86785.html) specification for PhotoID mDoc documents. This schema is designed to support equivalent claims, facilitating interoperability and standardization for digital identity documents in SD-JWT format.

## Overview

The JSON Schema in this repository mirrors the claims and structure defined in the ISO/IEC TS 23220-4 specification for mDoc (mobile document) Photo ID documents. It organizes claims into three primary nodes, each corresponding to an mDoc namespace, ensuring structured, compatible handling of verifiable credential data:

- iso23220: Contains core personal identification claims as defined by ISO/IEC 23220-1, such as name, birth date, document issue and expiry dates, and issuing authority details.
- photoid: Represents additional claims specific to the photo ID, covering attributes like personal identifiers, birthplace, residence details, and travel document number.
- dtc: Includes DTC (Data Transfer Container) claims, organizing groups of data (Data Groups 1-16) and cryptographic information (Security Object Document) necessary for secure document exchange and validation.
