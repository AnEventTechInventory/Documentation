# API on QR-Codes

## Introduction

The QR-Code API endpoint is used to create Any QR-Codes. For existing devices, users, locations and actions codes 
can be requested. Also any custom data can be encoded into a QR-Code.

## Destination

### For existing

For any existing item the QR-Code can be requested on the following endpoints:

`/api/v1/{type}/{id}/qr-code`

The type can be one of the following:
- device
- user
- location
- action

For custom data the following endpoint can be used:

`/api/v1/qr-code?data={data}?error_correction={error_correction}?format={format}`

## Format

### svg

If svg is requested no additional information is returned. The svg is returned as a string.

### png

If png is requested, additionally the size of the image can be requested. The size is given in pixels. The default 
value is 500. The size can be requested using the following parameter:

`?size={size}`


<tip>
The image is returned as a base64 encoded string. The non-black pixels are transparent. Keep in mind that for too 
small pixel sizes the QR-Code might not be readable anymore.
</tip>
