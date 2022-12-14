# Realtime Badge in React Native and PubNub

⚠️ This tutorial is out of date: While this tutorial series contains useful information, this post was originally written using PubNub's React SDK V1. Check out our [React SDK Docs](https://www.pubnub.com/docs/sdks/react) for an up-to-date reference. You can learn more about how PubNub powers [thousands of customers](https://www.pubnub.com/customers/) worldwide in our [PubNub for Developers](https://www.pubnub.com/developers/) resources. Have suggestions or questions about the content of this post? Reach out to devrel@pubnub.com.⚠️

In this [tutorial](https://www.pubnub.com/blog/how-to-add-a-realtime-badge-to-icons-in-react-native/), you will be using React Native libraries to clone Facebook Messenger and add badges to the icons. PubNub will be used to power the real-time updates to the badge via the [PubNub React SDK](https://www.pubnub.com/docs/sdks/react). The final result will be a simple application that looks as follows.

![PubNub Realtime Presence Badge Gif](https://media.giphy.com/media/MFmLnJKpRo9YXqbd1I/giphy.gif)

You can follow the step-by-step tutorial to build this application on PubNub's website.

## Environment Setup
In order to start the development process, you are going to need to prepare a few prerequisites.
* Visual Studio Code.
* A [PubNub Account](https://admin.pubnub.com/#/login). A PubNub account is always free, and is necessary to obtain the API keys necessary for online play. Enable [Presence](https://www.pubnub.com/how-to/admin-portal-presence/) and [Message Persistence](https://www.pubnub.com/how-to/admin-portal-persistence/). Learn more about how to create keys with this written and video [walkthrough](https://www.pubnub.com/how-to/admin-portal-create-keys/), specifically for Presence and Message Persistence. Copy the publish and subscribe keys to a text editor, as you'll need these later on.
* Node.js
* Terminal / Console
* XCode (for iOS simulation)
* Android Studio (for Android simulation)
* Install React Native CLI
```
sudo npm install -g react-native-cli
sudo npm install -g react-native
```
## Build & Run

Once you've obtained your PubNub publish/subscribe keys from signing up earlier, place these when initializing PubNub in the constructor in App.js.
Save any changes, and then run the application by entering the following commands.

 ```
 npm i
 react-native link
 ```
 Then run the application on either iOS or Android devices.

 ```react-native run-ios``` or ```react-native run-android```

## Links
- PubNub Account: https://admin.pubnub.com/#/login
- React SDK: https://www.pubnub.com/docs/sdks/react
- Tutorial Link: https://www.pubnub.com/blog/how-to-add-a-realtime-badge-to-icons-in-react-native/

## License
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
