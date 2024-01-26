# Devices

## Introduction

A device represents a single physical device. The device contains [type](type.md) information. New devices can 
be created by hand. If at one point the user added a [EAN, GTIN or similar](adding-ean.md) to a type. The device can 
simply be created by scanning the barcode. The same applies for scanning a QR-code of another device.

## Contents

| Name       | Datentyp                    | Required | Link | Comment |
|------------|-----------------------------|----------|------|---------|
| Type       | [Type](type.md)             | yes      |      |         |
| Electrical | [Electrical](electrical.md) | yes      |      |         |
| Location   | [Location](location.md)     | yes      |      |         |
| Contents   | Device[]                    | no       |      |         |
