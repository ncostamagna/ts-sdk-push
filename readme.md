# Setup

```
npm login
```

# Project

typescript sdk project which performs the communication with **Push Notify API** androind application:
https://play.google.com/store/apps/details?id=net.xdroid.pn&hl=en&gl=US

# Install

You must run for installing the sdk

```
npm install ts-sdk-push
```

# Exaples

You must import the **PushSDK** class from **ts-sdk-push**

```ts
import { PushSDK } from "ts-sdk-push";
```

And this is a simple example about 'How can I run the sdk?'

```ts
const sdk = new PushSDK("[url base]", "[my token]");

const res = await this.pushSDK.push("[my title]", "[my message]", "[my url]");
```
