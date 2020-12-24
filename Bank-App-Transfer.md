# Bank-App-Transfer-Auto

Transfer Auto **Bank Thai** _(Android Device)_ support **KPlus**, **SCB Easy**

- [Want to use](#want-to-use)
- [Installation](#installation)
- [Update](#update)
- [Config](#config)
- [Start Program](#start-program)
- [Get Device ID](#how-to-get-device-id)

## Want to use

  Contact Developer Line ID : [@nwsoft](https://line.me/ti/p/@nwsoft)


## Installation

- Install [Git](https://git-scm.com/download/win) to <code>C:\88Auto-System\_System\Git</code>

  - Open Terminal
    ```
    cd C:\
    git clone https://github.com/NamwanSoftTH/Bank-App-Transfer.git 88Auto
    Username: NamwanSoftTH
    Password: {{Personnel Token}}
    ```

- Install [Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html) to <code>C:\88Auto-System\_System\JDK</code>

- Install [Android Studio](https://developer.android.com/studio/index.html)

  - Set SDK Path to <code>C:\88Auto-System\_System\AndroidSDK</code>
  - Download SDK from **SDK Manager** in **Android Studio**

- Install [NodeJS](https://nodejs.org/en/) (Use **LTS Version**) to <code>C:\88Auto-System\_System\NodeJS</code>

- Install [Python](https://www.python.org/downloads/) to <code>C:\88Auto-System\_System\Python</code>

- Set Path Environmental Variable

  - Go to <code>C:\88Auto\_System\_Install</code>
  - Right click _Run as administrator_ **\_SetVarible.bat**

- Open Terminal

```
cd C:\88Auto-System
npm install -g appium
npm install -g appium-doctor
pip install robotframework
pip install robotframework-appiumlibrary
pip install -U requests
pip install -U robotframework-requests
pip install robotframework-httplibrary
```

- Check Status

```
git --version
node -v
python --version
appium -v
```

## Update

```
C:\88Auto
git pull
```

## Config

Go to <code>C:\88Auto\_System\_App</code> and edit config file **\_Script-{Bank}-{Device Number}**

- change **${API_URL}**
- change **${DEVICE_VERSION}**
- change **${DEVICE_ID}**
- change **${APP_PIN_1}**
- change **${APP_PIN_2}**
- change **${APP_PIN_3}**
- change **${APP_PIN_4}**
- change **${APP_PIN_5}**
- change **${APP_PIN_6}**
- change **${LINE_TOKEN}** not fix

## Start Program

Go to <code>C:\88Auto</code> double click **\_Run\_{Bank}.bat** after enter _{Device Number}_

## How to get Device ID

Run command in terminal <code>adb devices</code>
