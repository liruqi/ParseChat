## OVERVIEW

This is a full native iPhone app to create text based group or private chat with Parse, with latency less than 5 seconds.

![Chat](http://relatedcode.com/github/chat817.png)
.
![Chat](http://relatedcode.com/github/chat803.png)
.
![Chat](http://relatedcode.com/github/chat818.png)

![Chat](http://relatedcode.com/github/chat804.png)
.
![Chat](http://relatedcode.com/github/chat806.png)
.
![Chat](http://relatedcode.com/github/chat819.png)

The app is using Parse as backend which is basically free. (Free plan: 20 GB File Storage, 20 GB Database Storage, 2 TB Data Transfer, 30 req/s).

## FEATURES

- Chat between multiple devices
- Group chat functionality
- Private chat functionality
- Single or Multiple recipients
- No backend programming needed
- Native and easy to customize user interface
- Push Notification support
- Login with Email
- Login with Facebook
- Login with Twitter
- Sending text messages
- Sending pictures
- Sending videos
- Sending large emojis
- Address Book friend list
- Invite functionality - SMS, email
- Facebook friend list (list only registered users)
- Recent view for ongoing chats
- Picture view for pictures
- Basic Settings view included
- Profile view for users
- Group settings view for groups
- Blocked view for blocked users
- Privacy Policy view
- Terms of Service view
- Facebook profile picture grabbed automatically
- Twitter profile picture grabbed automatically (<i>coming soon</i>)
- Picture, video and audio upload progress indicator
- Video length limit possibility
- Copy and paste text messages
- Send button is enabled/disabled automatically
- Arbitrary message sizes
- Data detectors - phone numbers, links, dates
- Timestamps possibilities
- Hide keyboard with swipe down
- Smooth animations
- Send/Receive sound effects
- Deployment target: iOS 8
- Supported devices: iPhone 4S/5/5C/5S/6/6 Plus

---

![Chat](http://relatedcode.com/github/chat809.png)
.
![Chat](http://relatedcode.com/github/chat811.png)
.
![Chat](http://relatedcode.com/github/chat812.png)


## REQUIREMENTS

- Xcode 7
- iOS 8
- ARC

## INSTALLATION

**1.,** All source files located in *Classes* directory. Vendor files located in *Vendor* directory and external Frameworks in *Framework* directory. Some resource files can be found in *Resources* directory. Simply add *Classes*, *Resources*, *Vendor* and *Framework* directories to your project.

**2.,** You also need the latest Parse SDK. (Already included, but you can download from [here](https://www.parse.com/docs/downloads)).

To add Parse.framework just unzip the downloaded file and drag the Parse.framework folder into your Xcode project under 'Frameworks'.

More info about how to [install](https://www.parse.com/apps/quickstart#parse_data/mobile/ios/native/existing) Parse SDK.

**3.,** You also need the latest Facebook SDK. (Already included, but you can download from [here](https://developers.facebook.com/docs/ios)).

To add FacebookSDK.framework just drag the FacebookSDK.framework folder into your Xcode project under 'Frameworks'.

More info about how to [install](https://developers.facebook.com/docs/ios/getting-started) Facebook SDK.

**4.,** You also need several external libraries which are included. But if you need, you can download them from here:

https://github.com/ideaismobile/IDMPhotoBrowser<br>
https://github.com/jessesquires/JSQMessagesViewController<br>
https://github.com/jessesquires/JSQSystemSoundPlayer<br>
https://github.com/relatedcode/ProgressHUD<br>
https://github.com/rnystrom/RNGridMenu<br>
https://github.com/rs/SDWebImage<br>

To use these libraries, just add IDMPhotoBrowser, JSQMessagesViewController, JSQSystemSoundPlayer, ProgressHUD, RNGridMenu and SDWebImage directories to your project.

**5.,** You need to [register](https://developers.facebook.com/apps) your app at Facebook. More info about how to [configure](https://developers.facebook.com/docs/ios/getting-started) Facebook.

**6.,** You need to use your own [Parse account](https://www.parse.com/#signup).

**7.,** You need to [configure](https://www.parse.com/tutorials/ios-push-notifications) Push Notification.

**8.,** Please replace the existing Parse account details in *AppDelegate.m*.

**9.,** Please replace the existing Facebook account details in *Info.plist*.


## CONTACT

Do you have any questions or idea? My email is: info@relatedcode.com or you can find some more info at [relatedcode.com](http://relatedcode.com)

## LICENSE

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
