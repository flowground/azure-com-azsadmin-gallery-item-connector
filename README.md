# ![LOGO](logo.png) GalleryManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the GalleryManagementClient API (version 2015-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-GalleryItem/2015-04-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:36+03:00

## API Description

The Admin Gallery Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists gallery items.

*Tags:* `GalleryItems`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Uploads a provider gallery item to the storage.

*Tags:* `GalleryItems`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

### Delete a specific gallery item.

*Tags:* `GalleryItems`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `galleryItemName` - _required_ - Identity of the gallery item. Includes publisher name, item name, and may include version separated by period character.
* `api-version` - _required_ - Client API Version.

### Get a specific gallery item.

*Tags:* `GalleryItems`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `galleryItemName` - _required_ - Identity of the gallery item. Includes publisher name, item name, and may include version separated by period character.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-gallery-item-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
