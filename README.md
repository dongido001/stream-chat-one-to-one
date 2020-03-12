## Build a one-to-one chat app using Stream chat and JavaScript

This application is basic implementaion of a one to one chat app built with [Stream Chat API](https://getstream.io/chat/).

## How to install

After clonning the app to your system, run the below command:

1. Go to the server.js file and update the `<STREAM_API_KEY>` and `<STREAM_API_SECRET>` placeholders with your correct API KEY and SECRET respectively (which you can get from your [Stream Dashboard](https://getstream.io/blog/build-a-chat-messaging-platform-in-php/#creating-a-stream-account))

2. Go to the `public/custom.js` file and update `<STREAM_API_KEY>` placeholder with your correct API key.

3. Install the packages

```
npm install
```

4. Start up the Node server and then start chatting!

```
node server.js
```