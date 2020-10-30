# AndroidRTC

You can find the orginal version of this at https://github.com/Jeffiano/ScreenShareRTC.

The only change I made is that when the call is ready, the ID of the stream session is copied to the clipboard, so you can use that ID to view the android screen remotely, without using the Web application client.

## WebRTC Live Streaming

An Android client for [ProjectRTC](https://github.com/pchab/ProjectRTC).

It is designed to demonstrate WebRTC screen share between androids and/or desktop browsers.

## How To

You need [ProjectRTC](https://github.com/pchab/ProjectRTC) up and running, and it must be somewhere that your android can access. (You can quickly test this with your android browser). Modify the host string (in res/values/strings.xml) to the server IP.


Your stream should appear as "android_device_stream" in ProjectRTC, so you can also use the view feature there.

## Libraries

### [libjingle peerconnection](https://code.google.com/p/webrtc/)
### [socket.io-client](https://github.com/nkzawa/socket.io-client.java)

