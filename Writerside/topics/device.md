# Devices

## Introduction

A device represents a physical devices. These can contain other devices. No 
circular references are allowed. This is enforced by the API. The device 
contains different information about the device. This includes the name, 
type, manufacturer, etc.

## Contents

| Name         | Datentyp     | Required | Link                | Comment |
|--------------|--------------|----------|---------------------|---------|
| Manufacturer | Manufacturer | yes      | [[manufacturer.md]] |         |
| Type         | Type         | yes      | [[type.md]]         |         |
| Name         | String       | yes      |                     |         |
| Electrical   | Electrical   | yes      | [[electrical.md]]   |         |
| Description  | String       | no       |                     |         |
| Devices      | Device[]     | no       |                     |         |
| Custom       | Custom       | no       | [[custom.md]]       |         |

[Go To Top](#table-of-contents)