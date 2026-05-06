# 🔑 zerofido - Secure your accounts with Flipper Zero

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Agalancampillo/zerofido/releases)

zerofido turns your Flipper Zero into a physical security key. You use this tool to log in to websites using passkeys instead of passwords. It supports industry standards like FIDO2 and U2F to keep your online accounts safe from hackers. The app mimics a standard USB security key when you plug it into your computer.

## 🛠️ Requirements

You need the following items to use zerofido:

1. A Flipper Zero device.
2. A Windows 10 or Windows 11 computer with an available USB port.
3. The official Flipper Zero mobile app or QFlipper installed on your computer to move files to your device.

## 📥 Downloading the software

You must download the correct file from the project releases page to ensure compatibility with your Flipper Zero firmware.

[Visit the official download page here](https://github.com/Agalancampillo/zerofido/releases)

1. Open your web browser.
2. Navigate to the link above.
3. Look for the section labeled "Assets" under the most recent version.
4. Click the file ending in `.fap` to save it to your computer.
5. Keep this file in an easy-to-find location like your Downloads folder.

## 🔌 Installing on your Flipper Zero

Follow these steps to move the application onto your hardware:

1. Connect your Flipper Zero to your computer using the provided USB cable.
2. Open the QFlipper software on your computer.
3. Click the "File Manager" icon.
4. Locate the folder named "apps" on your Flipper Zero storage.
5. Drag the `.fap` file you downloaded earlier into the "apps" folder.
6. Wait for the transfer to finish.
7. Disconnect the Flipper Zero from your computer.

## 🚀 Running zerofido

1. Wake your Flipper Zero.
2. Press the main button to open the menu.
3. Navigate to the "Applications" folder.
4. Select "Tools" or "USB" depending on your firmware version.
5. Locate and select "zerofido" from the list of installed apps.
6. The screen shows the current status of the connection.

## 🔐 Setting up your credentials

Websites handle passkeys in different ways. Follow these steps to link your Flipper Zero to a service:

1. Log in to the service or website you want to secure.
2. Go to the "Security" or "Login Settings" section.
3. Select the option to "Add a Security Key" or "Add a Passkey."
4. Your computer prompts you to insert a security key.
5. Plug your Flipper Zero into your computer USB port.
6. The Flipper Zero detects the request and displays a prompt on its screen.
7. Confirm the action using the buttons on your Flipper Zero.
8. The service confirms that you registered the device.

## 🛡️ Daily use

You no longer need to type long passwords for services that support passkeys. 

1. Go to the login page of your chosen service.
2. Choose "Sign in with passkey" or "Use security key."
3. Plugin your Flipper Zero when prompted.
4. If asked, select the Flipper Zero from your computer security menu.
5. Approve the login request on your Flipper Zero screen.
6. The website grants you access.

## ❓ Troubleshooting common issues

If you encounter problems, check these areas first:

* Connection issues: Ensure the USB cable remains secure while the Flipper Zero performs the handshake with your computer.
* Device recognition: Some computers require a moment to recognize the Flipper Zero as a HID device. Wait five seconds after plugging it in before attempting to sign in.
* Firmware updates: Ensure your Flipper Zero runs the latest version of the official firmware or your preferred custom firmware. Outdated firmware can prevent the app from communicating with the USB port.
* Multiple keys: Do not keep other security keys plugged into your computer at the same time. This confuses the computer when it tries to authenticate your account.

## ⚙️ Understanding the technology

zerofido bridges the gap between your physical device and modern security protocols. It follows the FIDO2 standard, which uses public-key cryptography. This means the service you access never learns your actual secret key. Instead, the service verifies that you possess the Flipper Zero. This method protects you even if a website experiences a data breach, because your private data remains stored offline on your device at all times. 

## ⚖️ Security best practices

Treat your Flipper Zero with the same care as your house keys. Because this device provides access to your digital accounts, keep it in a safe location. If you lose your Flipper Zero, use your service backup codes or secondary recovery methods immediately to protect your accounts. You should always register at least two different security keys or recovery methods for every account you link to zerofido. This ensures you do not lock yourself out if your primary device breaks or goes missing.