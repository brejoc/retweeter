# retweeter

## Building

Just doing a `go build` should be enough, since all the depencies are vendorized.

## Settings

retweeter is getting the settings from env variables. For local testing you can e.g. use [direnv](https://direnv.net/).

In order to use the retweeter you need the following settings/env variables:

* `CONSUMER_KEY`
* `CONSUMER_SECRET`
* `ACCESS_TOKEN`
* `ACCESS_TOKEN_SECRET`

And of course the `TWITTER_HASHTAG` you want to listen to. The token and consumer settings can be found on Twitter's [devloper page](https://developer.twitter.com/).

## Deployment

To deploy retweeter on a Linux with Systemd, you can use the [`retweeter.service.example`](https://github.com/brejoc/retweeter/blob/master/retweeter.service.example). 

## Misc

This retweeter is a fork of https://github.com/campoy/justforfunc/tree/master/14-twitterbot
