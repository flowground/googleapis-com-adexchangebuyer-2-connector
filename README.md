# ![LOGO](logo.png) Ad Exchange Buyer API II **flow**ground Connector

## Description

A generated **flow**ground connector for the Ad Exchange Buyer API II API (version v2beta1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/adexchangebuyer2/v2beta1/swagger.json<br/>
Generated at: 2019-05-07T17:41:05+03:00

## API Description

Accesses the latest features for managing Ad Exchange accounts, Real-Time Bidding configurations and auction metrics, and Marketplace programmatic deals.

## Authorization

Supported authorization schemes:
- OAuth2
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all the clients for the current sponsor buyer.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Creates a new client buyer.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Gets a client buyer with a given client account ID.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Updates an existing client buyer.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Lists all the client users invitations for a client<br/>
> with a given account ID.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Creates and sends out an email invitation to access<br/>
> an Ad Exchange client buyer account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Retrieves an existing client user invitation.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `invitationId` - _required_
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Lists all the known client users for a specified<br/>
> sponsor buyer account ID.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Retrieves an existing client user.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `userId` - _required_
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Updates an existing client user.<br/>
> Only the user status can be changed on update.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `clientAccountId` - _required_
* `userId` - _required_
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Lists creatives.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Creates a creative.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Gets a creative.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `creativeId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Updates a creative.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `creativeId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### List all creative-deal associations.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `creativeId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Associate an existing deal with a creative.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `creativeId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Remove the association between a deal and a creative.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `creativeId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Stops watching a creative. Will stop push notifications being sent to the<br/>
> topics when the creative changes status.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `creativeId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Watches a creative. Will result in push notifications being sent to the<br/>
> topic when the creative changes status.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_
* `creativeId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `callback` - _optional_ - JSONP
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `access_token` - _optional_ - OAuth access token.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `bearer_token` - _optional_ - OAuth bearer token.

### Lists all metrics that are measured in terms of number of bids.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all errors that occurred in bid responses, with the number of bid<br/>
> responses affected for each reason.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all reasons for which bid responses were considered to have no<br/>
> applicable bids, with the number of bid responses affected for each reason.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all reasons that caused a bid request not to be sent for an<br/>
> impression, with the number of bid requests not sent for each reason.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all reasons for which bids were filtered, with the number of bids<br/>
> filtered for each reason.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all creatives associated with a specific reason for which bids were<br/>
> filtered, with the number of bids filtered for each creative.

*Tags:* `bidders`

#### Input Parameters
* `creativeStatusId` - _required_
* `filterSetName` - _required_
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all details associated with a specific reason for which bids were<br/>
> filtered, with the number of bids filtered for each detail.

*Tags:* `bidders`

#### Input Parameters
* `creativeStatusId` - _required_
* `filterSetName` - _required_
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Lists all metrics that are measured in terms of number of impressions.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all reasons for which bids lost in the auction, with the number of<br/>
> bids that lost for each reason.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### List all reasons for which winning bids were not billable, with the number<br/>
> of bids not billed for each reason.

*Tags:* `bidders`

#### Input Parameters
* `filterSetName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Deletes the requested filter set from the account with the given account<br/>
> ID.

*Tags:* `bidders`

#### Input Parameters
* `name` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Retrieves the requested filter set for the account with the given account<br/>
> ID.

*Tags:* `bidders`

#### Input Parameters
* `name` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Lists all filter sets for the account with the given account ID.

*Tags:* `bidders`

#### Input Parameters
* `ownerName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Creates the specified filter set for the account with the given account ID.

*Tags:* `bidders`

#### Input Parameters
* `ownerName` - _required_
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `bearer_token` - _optional_ - OAuth bearer token.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `pp` - _optional_ - Pretty-print response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

## License

**flow**ground :- Telekom iPaaS / googleapis-com-adexchangebuyer-2-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
