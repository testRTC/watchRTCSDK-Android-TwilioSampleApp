# WatchRTC Twilio sample application
This is the WatchRTC Android Twilio sample application. The project reference from the Twilio sample application. The main purpose of this project is 'How to implement WatchRTC Android SDK with Twilio WebRTC SDK'.

WatchRTC
-----------
- Generate WatchRTC_api_key and update in `WatchRTCConfig`.
- WatchRTC SDK integration code will located in `VideoActivity.kt` file 
- We have used WatchRTC SDK version 1.0.0 in this sample app.

Twilio Video Quickstart for Android
-----------
Step to use,
- Import this project into the latest Android studio i.e. 'Electric Eel | 2022.1.1' and above
- Generate an Access Token
-- View instructions here for how to generate an Access Token using the [Twilio CLI](https://www.twilio.com/docs/video/tutorials/user-identity-access-tokens#generate-cli). 
-- Generating Access Tokens with the Twilio CLI is a quick way to get an Access Token for testing and development purposes only. 
-- Need to generate access token for each phone/emulator. 
- Add the access token string copied from the console to a variable named 'phone1Token' & 'phone2Token' in your local.properties file.
`phone1Token=abcde450123456789`
`phone2Token=fghij691234563215`
- Run the quickstartKotlin app on two Android devices or emulator.
- Press the video call button at the bottom right portion of the screen and type a room name to connect to a Room. In both device room name should be same.
- On another device, use an additional access token with a different identity to connect to the same room.
- The generated token have short expiry time so whenever you get `Failed to connect` error in the application then need to generate token and again and rerun the application.

Further Reading
-----------
- Read more about [Twilio sample](https://github.com/twilio/video-quickstart-android#quickstart)
- [WatchRTC SDK](https://github.com/testRTC/watchRTCSDK-Android)
- [WatchRTC Sample application](https://github.com/testRTC/watchRTCSDK-Android-SampleApp)
- [WatchRTC Vonage Sample application](https://github.com/testRTC/watchRTCSDK-Android-VonageSampleApp)
