# BeReal Inspired iOS App

A photo-sharing iOS app built with Swift in Xcode. Users can create an account, share a photo with a caption, and view other users' posts after uploading their own. The feed shows up to 10 recent posts from the last day. Older posts are filtered out of the feed. 

By: **Snezhana Valtchouk**

## Features
- [x] Account registration and login: Create an account and sign in.
- [x] Photo sharing: Take a photo with the camera or choose one from the photo library, ability to add a caption.
- [x] Post-to-view feed: Upload a post to unlock viewing of other users' photos.
- [x] Persistent sessions: Stay signed in when the app is closed and reopened.
- [x] Logout: Sign out and return to the login screen.
- [x] Pull-to-refresh: Reload the feed with a loading indicator.

## Technologies
- [x] Swift
- [x] Xcode
- [x] iOS
- [x] ParseSwift for authentication and backend data
 
## Video Walkthrough

Quick walkthrough:

![ezgif-5-d45a3abdcc](https://user-images.githubusercontent.com/110207696/229680334-5b96fe8a-5bcd-4a7d-9821-cb8fbb9d7b75.gif)


Logging out of a previous account and signing up for a new one:

![ezgif-2-ba2086551e](https://user-images.githubusercontent.com/110207696/228135720-90cd60ec-69b2-404b-b4b2-f47c70c32da8.gif)


Logging into the account that was created and posting from it:

![ezgif-2-44b79612a9](https://user-images.githubusercontent.com/110207696/228135744-7f7a60d2-79c7-475f-9edb-dea3f7a40aee.gif)


User is able presistent login credentials and view recent posts:

![ezgif-2-e10e878e8e](https://user-images.githubusercontent.com/110207696/228135522-2e3634c6-5e7f-48ca-bfac-88c31266baa4.gif)

GIF created with ezgif


## Notes
During development, I worked through an unresponsive logout button and a runtime crash caused by unexpectedly wrapping a nil optional. These issues gave me practice debugging user interactions and handling optional values in Swift. 

## License

    Copyright [2023] [Snezhana Valtchouk]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
