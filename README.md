# ![LOGO](logo.png) ServerManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the ServerManagement API (version 2016-07-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/servermanagement/2016-07-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:56+03:00

## API Description

REST API for Azure Server Management Service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns gateways in a subscription.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Lists nodes in a subscription.

*Tags:* `Nodes`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Returns gateways in a resource group.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.

### Deletes a gateway from a resource group.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `gatewayName` - _required_ - The gateway name (256 characters maximum).

### Gets a gateway.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `gatewayName` - _required_ - The gateway name (256 characters maximum)
* `$expand` - _optional_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
    Possible values: status, download.

### Updates a gateway belonging to a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `gatewayName` - _required_ - The gateway name (256 characters maximum).

### Creates or updates a ManagementService gateway.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `gatewayName` - _required_ - The gateway name (256 characters maximum).

### Gets a gateway profile.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `gatewayName` - _required_ - The gateway name (256 characters maximum).

### Regenerate a gateway's profile

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `gatewayName` - _required_ - The gateway name (256 characters maximum).

### Upgrades a gateway.

*Tags:* `Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `gatewayName` - _required_ - The gateway name (256 characters maximum).

### Lists nodes in a resource group.

*Tags:* `Nodes`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.

### deletes a management node

*Tags:* `Nodes`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).

### Gets a management node.

*Tags:* `Nodes`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).

### Updates a management node.

*Tags:* `Nodes`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).

### Creates or updates a management node.

*Tags:* `Nodes`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).

### Deletes a session for a node.

*Tags:* `Sessions`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.

### Gets a session for a node.

*Tags:* `Sessions`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.

### Creates a session for a node.

*Tags:* `Sessions`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.

### Gets a list of the active sessions.

*Tags:* `PowerShell`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.

### Gets the status of a command.

*Tags:* `PowerShell`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.
* `pssession` - _required_ - The PowerShell sessionId from the user.
* `$expand` - _optional_ - Gets current output from an ongoing call.
    Possible values: output.

### Updates a running PowerShell command with more data.

*Tags:* `PowerShell`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.
* `pssession` - _required_ - The PowerShell sessionId from the user.

### Creates a PowerShell session.

*Tags:* `PowerShell`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.
* `pssession` - _required_ - The PowerShell sessionId from the user.

### Cancels a PowerShell command.

*Tags:* `PowerShell`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.
* `pssession` - _required_ - The PowerShell sessionId from the user.

### Creates a PowerShell script and invokes it.

*Tags:* `PowerShell`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.
* `pssession` - _required_ - The PowerShell sessionId from the user.

### Gets tab completion values for a command.

*Tags:* `PowerShell`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `resourceGroupName` - _required_ - The resource group name uniquely identifies the resource group within the user subscriptionId.
* `nodeName` - _required_ - The node name (256 characters maximum).
* `session` - _required_ - The sessionId from the user.
* `pssession` - _required_ - The PowerShell sessionId from the user.

## License

**flow**ground :- Telekom iPaaS / azure-com-servermanagement-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
