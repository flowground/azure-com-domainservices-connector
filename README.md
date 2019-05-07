# ![LOGO](logo.png) Domain Services Resource Provider **flow**ground Connector

## Description

A generated **flow**ground connector for the Domain Services Resource Provider API (version 2017-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/domainservices/2017-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:06+03:00

## API Description

The AAD Domain Services API.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all the available Domain Services operations.

*Tags:* `DomainServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### List Domain Services in Subscription (GET Resources)

> The List Domain Services in Subscription operation lists all the domain services available under the given subscription (and across all resource groups within that subscription).

*Tags:* `DomainServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### List Domain Services in Resource Group (GET Resources)

> The List Domain Services in Resource Group operation lists all the domain services available under the given resource group.

*Tags:* `DomainServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.

### Delete Domain Service (DELETE Resource)

> The Delete Domain Service operation deletes an existing Domain Service.

*Tags:* `DomainServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `domainServiceName` - _required_ - The name of the domain service.

### Get Domain Service (GET Resources)

> The Get Domain Service operation retrieves a json representation of the Domain Service.

*Tags:* `DomainServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `domainServiceName` - _required_ - The name of the domain service.

### Update Domain Service (PATCH Resource)

> The Update Domain Service operation can be used to update the existing deployment. The update call only supports the properties listed in the PATCH body.

*Tags:* `DomainServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `domainServiceName` - _required_ - The name of the domain service.

### Create or Update Domain Service (PUT Resource)

> The Create Domain Service operation creates a new domain service with the specified parameters. If the specific service already exists, then any patchable properties will be updated and any immutable properties will remain unchanged.

*Tags:* `DomainServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `domainServiceName` - _required_ - The name of the domain service.

## License

**flow**ground :- Telekom iPaaS / azure-com-domainservices-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
