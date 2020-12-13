# WiFi-Direct-File-Transfer
WiFi Direct File Transfer is an app that will allow sharing of data between Android devices running Android 4.0 or higher using a WiFi direct connection without the use of a WiFi access point. This will enable data transfer between devices without relying on any existing network infrastructure
<br>

<br>

### Recommended Reading

[General Overview](http://developer.android.com/guide/topics/connectivity/wifip2p.html)  
[Service Discovery](http://developer.android.com/training/connect-devices-wirelessly/nsd-wifi-direct.html)

WARNING: The app requires WifiP2pManager class. Does not work in an Android emulator

## Requirements
- Android Studio
- Physical devices

WiFi Direct File Transfer works with good performances.<br/>
The primary limitations are the "Discovery Phase" of this protocol and the Wi-Fi Direct's implementation in Android:<br/>
1. The discovery time is proportional to the number of devices <br/>
2. After a certain time, when a device is no longer discoverable, you may need to restart the Discovery Phase on all devices <br/>

## Features

1. Shows a list of nearby devices<br/>
2. Manage connection/disconnection between devices<br/>
3. Send multiple files between two devices<br/>
4. View device information without disconnection<br/>
5. Auto restart servers to receive files and device information.

<br/>

## Usage
### General usage
1. Activate Wi-Fi Direct on all devices.
2. Open the app on all devices.
3. App will auto discover peers.
4. Сhoose the device from peers list to connect.
6. App will auto-open file chooser.
7. Choose the files to send.
8. Select the files and done!

### Limitations

If you have a trouble connecting to peers:

- Try reconnecting, if reconnection is successful, it will auto-open file chooser.
- If you have any other issue, restart the app and wait about 60 seconds.

## License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

<br/>

## Screenshots

![Screenshot_2020-12-13-21-43-19-676_com app wi_fi_direct](https://user-images.githubusercontent.com/12817953/102018278-61303180-3d92-11eb-81bf-a967d0be5120.png)


![Screenshot_2020-12-13-21-44-33-732_com app wi_fi_direct](https://user-images.githubusercontent.com/12817953/102018280-64c3b880-3d92-11eb-9690-6445c150217c.png)


![Screenshot_2020-12-13-21-46-30-143_com app wi_fi_direct](https://user-images.githubusercontent.com/12817953/102018281-67bea900-3d92-11eb-81e0-5cc7511866bc.png)


![Screenshot_20201213-214400_Settings](https://user-images.githubusercontent.com/12817953/102018285-6ab99980-3d92-11eb-9073-41d32d9c9a34.jpg)


![Screenshot_20201213-214559_Wi-Fi Direct File Transfer](https://user-images.githubusercontent.com/12817953/102018287-6d1bf380-3d92-11eb-96dd-8d7ff063a0e6.jpg)


![Screenshot_20201213-214654_Wi-Fi Direct File Transfer](https://user-images.githubusercontent.com/12817953/102018291-70af7a80-3d92-11eb-8b44-2384db398caa.jpg)


