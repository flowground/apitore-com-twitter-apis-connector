# ![LOGO](logo.png) Twitter APIs MSP Connector

## Description

A generated MSP connector for the Twitter APIs API (version 0.0.2).

Generated from: https://api.apis.guru/v2/specs/apitore.com/twitterApis/0.0.2/swagger.json<br/>
Generated at: 2019-05-07T11:17:07+03:00

## API Description

Call Twitter APIs.<BR />[Endpoint] https://api.apitore.com/api/23

## Authorization

This API does not require authorization.

## Actions

### Get my tweets.

> Get my timeline tweets.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/twitter-response">twitter-response</a><BR />&nbsp; Class: com.apitore.banana.response.twitter.TwitterResponseEntity<BR />

*Tags:* `twitter-simple-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `sinceId` - _optional_ - Get after this id.
* `maxId` - _optional_ - Get before this id.
* `iter` - _optional_ - Numof requests. Return up to 200 x iter tweets.

### Get my tweets.

> Get my tweets.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/twitter-response">twitter-response</a><BR />&nbsp; Class: com.apitore.banana.response.twitter.TwitterResponseEntity<BR />

*Tags:* `twitter-simple-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `sinceId` - _optional_ - Get after this id.
* `maxId` - _optional_ - Get before this id.
* `iter` - _optional_ - Numof requests. Return up to 200 x iter tweets.

### Search tweets.

> Tweets search API.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/twitter-response">twitter-response</a><BR />&nbsp; Class: com.apitore.banana.response.twitter.TwitterResponseEntity<BR />

*Tags:* `twitter-simple-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `q` - _required_ - Search query
* `sinceId` - _optional_ - Search after this id.
* `maxId` - _optional_ - Search before this id.
* `iter` - _optional_ - Numof search requests. Return up to 100 x iter tweets.

## License

flowground :- Telekom iPaaS / apitore-com-twitter-apis-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
