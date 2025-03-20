# 🔗Unshorten Extension: Unshorten shortened Url's

## Introduction
Unshorten extension allows you to unshorten shortened url's and convert them to their long form without actually going to them.
This prevents chances to getting malwares from shortened urls as you know where the shortened url would lead to.

### About Unshorten api
> **Unshorten** is a free service to Un-Shorten the URLs created by URL shortening services. Unshorten[dot]me can un-shorten URLs created by different services like goo.gl (Google), fb[dot]me (Facebook), t[dot]co (Twitter), bit.ly, TinyURL, ow.ly among others

## Blocks
### Events

### 💛UnshortenSuccess
Triggered when unshorten is successful

**Parameters**

| Parameter | Type |
|-----------|------|
| resolvedUrl | text |
| usageCount | number |
| remainingCalls | number |

### 💛UnshortenFailed
Triggered when unshorten fails

**Parameters**

| Parameter | Type |
|-----------|------|
| error | text |

### Methods

### 💜UnshortenUrl
Unshorten a shortened URL

**Parameters**

| Parameter | Type |
|-----------|------|
| shortUrl | text |

## Download the extension for free :smile: 

This documentation was generated using AIX Tools (aixtools.ai2.sarthakdev.in) by @techxsarthak
