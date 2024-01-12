# Main

## Introduction

The goal of this project is to create an inventory system for event 
technology. This covers there are of material management, job management, 
personal management, etc.
The project is split into three parts. The documentation, the backend and 
the frontend. The documentation is written in markdown and converted to HTML 
using writerside and a [GitHub action][action-link].

![Build Status][action-badge]

[//]: # (Todo: add badges for other repos)

## Contents

### Data Types

The data types used in the project. The types are just an abstraction of the
implementation. Details are covered in the API documentation.

- [Device](device.md)
- [Manufacturer](manufacturer.md)

### Identification

Anything is identified by a [uuid](https://en.wikipedia.org/wiki/Universally_unique_identifier). 
The uuid are generated on creation of objects. If applicable the UUID should 
be put on devices as QR-Code on a sticker. The webapp can generate QR-codes.

To ease the usage the user is able to generate QR-codes for actions that 
happen often. [action-qr-code.md](action-qr-code.topic) contains a list of 
those actions and the content of the Codes if other systems for triggering 
are used. E.g. a macro keyboard.


## Links

[Documentation](https://github.com/AnEventTechInventory/Documentation)

[Backend](https://github.com/AnEventTechInventory/Backend)

[Frontend](https://github.com/AnEventTechInventory/Frontend)

[action-link]: https://github.com/AnEventTechInventory/Documentation/blob/main/.github/workflows/build.yml
[action-badge]: https://github.com/AnEventTechInventory/Documentation/actions/workflows/build.yml/badge.svg
