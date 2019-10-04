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

## Issues and Contributions

If you've got problems or questions please don't hesitate to open an issue. If you'd like to improve something or found a bug and you want to fix it, just open a pull request.

## Misc

This retweeter is a fork of https://github.com/campoy/justforfunc/tree/master/14-twitterbot
