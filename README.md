# Dial Pad App – Android (Java)

This is a simple Dial Pad Android application built using **Java** in **Android Studio**. It replicates the basic functionality of a phone dialer, allowing users to enter phone numbers and initiate calls via the native dialer.

https://github.com/Ilmaa2003/Dial-Pad-Using-Java-In-Android-Studio/blob/main/Interface.jpg
---

## Features

- Custom dial pad interface
- Direct call initiation using the native phone system
- Backspace/delete functionality
- Real-time number input display

---

## Tech Stack

- **Language**: Java  
- **IDE**: Android Studio  
- **Min SDK**: 21  
- **Target SDK**: 33  

---

## Setup Instructions

### Step 1: Extract the Project

- Download and extract the project ZIP file to your desired location.

---

### Step 2: Install Android Studio

Download from:  
[https://developer.android.com/studio](https://developer.android.com/studio)

Install and launch Android Studio.

---

### Step 3: Open the Project

1. Launch Android Studio and click **"Open an Existing Project"**
2. Browse to the extracted folder (e.g., `Phone/`)
3. Let Gradle sync and accept any prompts to update SDKs or plugins

---

### Step 4: Set Up an Emulator or Connect a Device

- Use the AVD Manager in Android Studio to create and launch an emulator,  
  **or**
- Connect a real Android device via USB with **Developer Options** and **USB debugging** enabled

---

### Step 5: Run the Application

1. Choose your target device from the toolbar
2. Click **Run** or press `Shift + F10` to launch the app

The Dial Pad app will open on the selected device.

---

## Permissions

Make sure to grant the following permission in your `AndroidManifest.xml`:

```xml
<uses-permission android:name="android.permission.CALL_PHONE" />
````

If using Android 6.0 (API 23) or higher, you must also request this permission at runtime.

---

## Use Cases

This application is suitable for:

* Beginners learning Android app development with Java
* Projects involving UI layout for numeric input
* Learning how to use `Intent.ACTION_CALL` to access system features

---

## License

This project is intended for **educational and demonstration purposes** only.

```

