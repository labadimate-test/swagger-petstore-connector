# ![LOGO](logo.png) Swagger Petstore **flow**ground Connector

## Description

A generated **flow**ground connector for the Swagger Petstore API (version 1.0.1).

Generated from: https://petstore.swagger.io/v2<br/>
Generated at: 2019-09-13T15:40:14+02:00

## API Description

This is a sample server Petstore server.  You can find out more about Swagger at [http://swagger.io](http://swagger.io) or on [irc.freenode.net, #swagger](http://swagger.io/irc/).  For this sample, you can use the api key `special-key` to test the authorization filters.<br/>

## Authorization

Supported authorization schemes:
- OAuth2
- API Key


For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Add a new pet to the store

*Tags:* `pet`

### Update an existing pet

*Tags:* `pet`

### Finds Pets by status
> Multiple status values can be provided with comma separated strings<br/>

*Tags:* `pet`

#### Input Parameters
* `status` - _required_ - Status values that need to be considered for filter<br/>

### Finds Pets by tags
> Multiple tags can be provided with comma separated strings. Use tag1, tag2, tag3 for testing.<br/>

*Tags:* `pet`

#### Input Parameters
* `tags` - _required_ - Tags to filter by<br/>

### Find pet by ID
> Returns a single pet<br/>

*Tags:* `pet`

#### Input Parameters
* `petId` - _required_ - ID of pet to return<br/>

### Updates a pet in the store with form data

*Tags:* `pet`

#### Input Parameters
* `petId` - _required_ - ID of pet that needs to be updated<br/>

### Deletes a pet

*Tags:* `pet`

#### Input Parameters
* `api_key` - _optional_
* `petId` - _required_ - Pet id to delete<br/>

### uploads an image

*Tags:* `pet`

#### Input Parameters
* `petId` - _required_ - ID of pet to update<br/>

### Returns pet inventories by status
> Returns a map of status codes to quantities<br/>

*Tags:* `store`

### Place an order for a pet

*Tags:* `store`

### Find purchase order by ID
> For valid response try integer IDs with value >= 1 and <= 10. Other values will generated exceptions<br/>

*Tags:* `store`

#### Input Parameters
* `orderId` - _required_ - ID of pet that needs to be fetched<br/>

### Delete purchase order by ID
> For valid response try integer IDs with positive integer value. Negative or non-integer values will generate API errors<br/>

*Tags:* `store`

#### Input Parameters
* `orderId` - _required_ - ID of the order that needs to be deleted<br/>

### Create user
> This can only be done by the logged in user.<br/>

*Tags:* `user`

### Creates list of users with given input array

*Tags:* `user`

### Creates list of users with given input array

*Tags:* `user`

### Logs user into the system

*Tags:* `user`

#### Input Parameters
* `username` - _required_ - The user name for login<br/>
* `password` - _required_ - The password for login in clear text<br/>

### Logs out current logged in user session

*Tags:* `user`

### Get user by user name

*Tags:* `user`

#### Input Parameters
* `username` - _required_ - The name that needs to be fetched. Use user1 for testing.<br/>

### Updated user
> This can only be done by the logged in user.<br/>

*Tags:* `user`

#### Input Parameters
* `username` - _required_ - name that need to be updated<br/>

### Delete user
> This can only be done by the logged in user.<br/>

*Tags:* `user`

#### Input Parameters
* `username` - _required_ - The name that needs to be deleted<br/>

## License

**flow**ground :- Telekom iPaaS / swagger-petstore-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
