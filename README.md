# ![LOGO](logo.png) DeviceServices **flow**ground Connector

## Description

A generated **flow**ground connector for the DeviceServices API (version 2018-02-16-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/windowsiot-WindowsIotServices/2018-02-16-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:29+03:00

## API Description

Use this API to manage the Windows IoT device services in your Azure subscription.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Windows IoT Services REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The version of the API.

### Check if a Windows IoT Device Service name is available.

*Tags:* `CheckDeviceServiceNameAvailability`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.

### Get all the IoT hubs in a subscription.

*Tags:* `DeviceServices`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.

### Get all the IoT hubs in a resource group.

*Tags:* `DeviceServices`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the Windows IoT Device Service.

### Delete a Windows IoT Device Service.

*Tags:* `DeviceServices`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the Windows IoT Device Service.
* `deviceName` - _required_ - The name of the Windows IoT Device Service.

### Get the non-security related metadata of a Windows IoT Device Service.

*Tags:* `DeviceServices`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the Windows IoT Device Service.
* `deviceName` - _required_ - The name of the Windows IoT Device Service.

### Updates the metadata of a Windows IoT Device Service.

> Updates the metadata of a Windows IoT Device Service. The usual pattern to modify a property is to retrieve the Windows IoT Device Service metadata and security metadata, and then combine them with the modified values in a new body to update the Windows IoT Device Service.

*Tags:* `DeviceServices`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the Windows IoT Device Service.
* `deviceName` - _required_ - The name of the Windows IoT Device Service.
* `If-Match` - _optional_ - ETag of the Windows IoT Device Service. Do not specify for creating a brand new Windows IoT Device Service. Required to update an existing Windows IoT Device Service.

### Create or update the metadata of a Windows IoT Device Service.

> Create or update the metadata of a Windows IoT Device Service. The usual pattern to modify a property is to retrieve the Windows IoT Device Service metadata and security metadata, and then combine them with the modified values in a new body to update the Windows IoT Device Service.

*Tags:* `DeviceServices`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the Windows IoT Device Service.
* `deviceName` - _required_ - The name of the Windows IoT Device Service.
* `If-Match` - _optional_ - ETag of the Windows IoT Device Service. Do not specify for creating a new Windows IoT Device Service. Required to update an existing Windows IoT Device Service.

## License

**flow**ground :- Telekom iPaaS / azure-com-windowsiot-windows-iot-services-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
