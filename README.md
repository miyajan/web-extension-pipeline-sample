# web-extension-pipeline-sample

Delivery Pipeline for Web Extension

## Setup

You need Client ID, Client Secret and Refresh Token for Chrome Web Store.

The following pages are helpful to get the credentials.

* https://developer.chrome.com/webstore/using_webstore_api
* https://github.com/DrewML/chrome-webstore-upload/blob/master/How%20to%20generate%20Google%20API%20keys.md

In this sample, the credentials are stored as environment variables ```CHROME_CLIENT_ID```, ```CHROME_CLIENT_SECRET``` and ```CHROME_REFRESH_TOKEN``` on CircleCI.
