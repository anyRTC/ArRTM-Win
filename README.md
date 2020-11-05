# anyRTC RTM Tutorial for Windows
*其他语言版本： [简体中文](README.zh.md)*

The anyRTC Windows Sample App is an open-source demo that will help you get message chat integrated directly into your Windows applications using the anyRTC RTM SDK.

With this sample app, you can:

- Login into RTM Serve
- Send point to point message and receive point to point message off line
- Display point to point history message
- Join channel
- Send channel message, receive channel message
- Leave channel
- Logout RTM server

## Running the App
First, create a developer account at [anyrtc.io](https://console.anyrtc.io/signin/), and obtain an App ID.
Then select the editor in the test project, click App Certificate, and get the App Certificate according to the operation.
Update "anyRTC-RTM-Tutorial-Windows/anyRTCRTM.ini" with your App ID and App Certificate.

```
[BaseInfo]
AppID=
AppCertificatedId=
```

## Developer Environment Requirements
- win7 above
- Visual Studio 2013

## Operating Instructions
- 1.Copy the corresponding files to the relevant directories in the SDK folder of the sln peer directory
- 2.Copy the anyRTC_rtm_sdk.dll file to the compile execution directory (debug/release)

## Connect Us
- You can find full API document at [Document Center](https://docs.anyrtc.io/)
- You can file bugs about this demo at [issue](https://github.com/anyRTC/ArRTM-Win/issues)

## License
The MIT License (MIT).
