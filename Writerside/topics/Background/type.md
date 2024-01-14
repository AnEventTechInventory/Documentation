# Type

The type describes the type of [device](device.md). The type contains common information for all devices of the 
same type.

## Contents

Entries in the table that contain `[]` may contain multiple or none.

| Name         | Datatype                         | Required | Description                                                  |
|--------------|----------------------------------|----------|--------------------------------------------------------------|
| Name         | String                           | yes      |                                                              |
| Description  | String                           | no       |                                                              |
| Manufacturer | [Manufacturer](manufacturer.md)  | yes      |                                                              |
| EAN          | String                           | no       | Can also be a GTIN or similar. multiple Entries are handled. |
| Image        | [Image](Image.md)                | no       |                                                              |
| Tags         | [Tag[]](type-tag.md)             | no       |                                                              |
| Properties   | [Property[]](custom-property.md) | no       |                                                              |
