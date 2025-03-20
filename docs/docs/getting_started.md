# Getting Started
## 📝 Overview   

The Getting Started guide provides a comprehensive walkthrough to help you begin using JED-FFM. It covers downloading and installing the app on Android or Windows, granting necessary permissions for optimal functionality, how to log into the app with your credentials or resetting your password if needed, and navigating the home page to access key features and tools. 

Furthermore, the guide includes instructions on how to access the extensions and features integrated with other apps such as; 

 - :material-microsoft-excel: Microsoft Excel  
 - :material-google-earth: Google Map & Google Earth  
 - :simple-whatsapp: WhatsApp  
 - :material-email: Email  
 - :fontawesome-solid-comment-sms: SMS  
 - 📞 Phone Call  

Follow these steps to ensure a smooth setup and start leveraging the app's capabilities.

## 📥 Download the App  
This guide will help you get started with downloading, installing, and setting up the app on your device. Whether you're using Android or Windows, follow the steps below to begin your journey with JED-FFM.

🔗 **[Download for Android](https://github.com/engr-iliyas/JED-FFM/releases/download/pilot/com.jed.ffm.1.0.0.1apk.apk)**  
🔗 **[Download for Windows](https://github.com/engr-iliyas/JED-FFM/releases/download/pilot/jed.ffm.windows.1.0.0.1.zip)**  

1. Click the link above to download the app for your device.
2. Wait for the download to complete.
3. Open the downloaded file to begin the installation process.
4. Follow the instructions below to install the app on your device.

!!! note
    For windows; extract the installation package from the downloaded ZIP file.

## 🛠 Install the App  

=== "Android"  
    1. Download the APK from the link above.  
    2. Open the download folder.
    3. Click `com.jed.ffm.<version>.apk` file and tap **Install**.  
    4. If prompted, enable **Install from Unknown Sources** in settings.  
    5. Open the app from your home screen.  
    !!! tip
        For quick access, move the app to your home screen as a shortcut. Long-press the app icon and select **Add to Home Screen** or dragit to your desired location.

=== "Windows"  

    !!! note
        Ensure that **Developer Mode** is enabled and **PowerShell scripts** are allowed in Windows settings before running the installation script.  
        [Learn how to enable Developer Mode](https://docs.microsoft.com/en-us/windowsapps/get-started/enable-your-device-for-development). 

    1. Download the installation package for windows from the link above.  
    2. Extract the Windows installer from the downloaded ZIP file.
    3. Open the extracted folder.
    4. Double-click on `Smartask.Client.Hybrid_<version>_x64.cer` to install the certificate.
    5. Open `Dependencies` folder and to install the runtime dependencies according to your system architecture.
    6. Go back to the extracted folder 
    7. Right-click on `install.ps` and tap **Run with PowerShell** to run the installation.
    7. Open the app from the Start Menu after installation.  

    !!! tip
        To quickly access the app, you can pin it to the taskbar or the Start menu.  
        - **Pin to Taskbar:** Right-click the app icon in the Start menu or after opening it, then select **Pin to taskbar**.  
        - **Pin to Start:** Right-click the app icon in the Start menu and select **Pin to Start**.  

## 📋 Granting Permissions  
The following table outlines the permissions required by the JED-FFM app for optimal functionality:  

| **Permission** | **Required** | **Description**                                                                    |
|----------------|--------------|------------------------------------------------------------------------------------|
| Location       | Yes          | Allows the app to access your location for geotagging and location-based features. |
| Camera         | No           | Enables the app to capture photos or scan QR codes.                                |
| Network Access | Yes          | Required for syncing data with the server.                                         |

=== "Android"  

    1. Open the **Settings** app on your Android device.  
    2. Navigate to **Apps** or **App Management** (this may vary depending on your device).  
    3. Locate and select **JED-FFM** from the list of installed apps.  
    4. Tap on **Permissions**.  
    5. Enable the required permissions:  
        - **Location**: Toggle the switch to allow location access.  
        - **Camera**: Toggle the switch to allow camera access.  
    6. Close the settings and reopen the app to ensure the permissions are applied.  
    !!! tip
        If you encounter issues, ensure that permissions are set to **Allow All the Time** for location and **Allow** for the camera.  

=== "Windows"  
    1. Open the **Settings** app on your Windows device.  
    2. Navigate to **Privacy & Security** > **Location**.  
    3. Scroll down to **App permissions** and click on **Location**.  
    4. Ensure that **Location Services** is turned on.
    4. Scroll down to find **FFM** in the list of apps.  
    5. Toggle the switch to enable location access for the app.  
    6. Restart the app to ensure the permissions are applied.  

    !!! tip
        If the app does not appear in the list, ensure it is installed correctly and try reopening it.  

!!! note
    Ensure all required permissions are granted to avoid functionality issues.  

<!-- <div style="display: flex; justify-content: space-between; margin-top: 20px;">
    <a href="../" style="background-color: #0078D4; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">← Previous</a>
    <a href="../login_page" style="background-color: #0078D4; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">Next →</a>
</div> -->

<div style="display: flex; justify-content: space-between; margin-top: 20px;" markdown>

[ :octicons-arrow-left-24: Previous ](index.md "Overview"){ .md-button .md-button--primary }
[ Next :octicons-arrow-right-24: ](login_page.md "Login Page"){ .md-button .md-button--primary }

</div>
