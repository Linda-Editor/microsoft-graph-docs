﻿# deviceManagement resource type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Singleton that acts as container for a collection of UserPFXCertificate entities.
## Methods
|Method|Return Type|Description|
|:---|:---|:---|
|[Get deviceManagement](../api/intune_raimportcerts_devicemanagement_get.md)|[deviceManagement](../resources/intune_raimportcerts_devicemanagement.md)|Read properties and relationships of the [deviceManagement](../resources/intune_raimportcerts_devicemanagement.md) object.|
|[Update deviceManagement](../api/intune_raimportcerts_devicemanagement_update.md)|[deviceManagement](../resources/intune_raimportcerts_devicemanagement.md)|Update the properties of a [deviceManagement](../resources/intune_raimportcerts_devicemanagement.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|Not yet documented|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|userPfxCertificates|[userPFXCertificate](../resources/intune_raimportcerts_userpfxcertificate.md) collection|Collection of PFX certificates associated with a user.|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagement"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagement",
  "id": "String (identifier)"
}
```


