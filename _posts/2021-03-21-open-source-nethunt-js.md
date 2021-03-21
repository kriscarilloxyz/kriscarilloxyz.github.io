---
title: "Open Source: Nethunt JS"
layout: post
categories: open-source nethunt javascript
---

A wrapper for [https://nethunt.com/integration-api](https://nethunt.com/integration-api) made with Javascript. 

Find source code on Github [https://github.com/montpcdev/nethunt-js/blob/master/index.js](https://github.com/montpcdev/nethunt-js/blob/master/index.js)

# Getting Started

Install package using NPM.

```console
npm i -S @kriscarilloxyz/nethunt-js
```

Import package and provide username and password.

```js
const Nethunt = require('@kriscarilloxyz/nethunt-js')
const client = new Nethunt('username', 'password')

const readableFolders = client.readableFolder()

"""
Example response:
[
    {
        "id": "596f644b8f6d05e16c24b810",
        "name": "My first folder"
    },
    {
        "id": "596f644b8f6d05e16c24b811",
        "name": "My second folder"
    }
]
"""
```

# Methods

- `client.readableFolder` [https://nethunt.com/integration-api#readable-folder](https://nethunt.com/integration-api#readable-folder)
- `client.writableFolder` [https://nethunt.com/integration-api#writable-folder](https://nethunt.com/integration-api#writable-folder)
- `client.folderField` [https://nethunt.com/integration-api#folder-field](https://nethunt.com/integration-api#folder-field)
- `client.findRecord` [https://nethunt.com/integration-api#find-record](https://nethunt.com/integration-api#find-record)
- `client.newRecord` [https://nethunt.com/integration-api#new-record](https://nethunt.com/integration-api#new-record)
- `client.newComment` [https://nethunt.com/integration-api#new-comment](https://nethunt.com/integration-api#new-comment)
- `client.updatedRecord` [https://nethunt.com/integration-api#updated-record](https://nethunt.com/integration-api#updated-record)
- `client.recordChange` [https://nethunt.com/integration-api#record-change](https://nethunt.com/integration-api#record-change)
- `client.createRecord` [https://nethunt.com/integration-api#create-record](https://nethunt.com/integration-api#create-record)
- `client.createComment` [https://nethunt.com/integration-api#create-comment](https://nethunt.com/integration-api#create-comment)
- `client.updateRecord` [https://nethunt.com/integration-api#update-record](https://nethunt.com/integration-api#update-record)
- `client.linkGmailThread` [https://nethunt.com/integration-api#link-gmail-thread](https://nethunt.com/integration-api#link-gmail-thread)
- `client.authTest` [https://nethunt.com/integration-api#auth-test](https://nethunt.com/integration-api#auth-test)