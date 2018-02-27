**Digital code signing basics**
===============================

Code signing is the process of signing the scripts with the help of certificate-based digital signature. The main purpose of such signing is to verify the identity of the authors and the authenticity of the code, so that other software and users could determine whether to trust the particular piece of software or not.

The code can be signed with a private or public key (SSH and SSL method alike) with the help of Microsoft code signing certificate. Upon the certificate request, a pair of public/private key is generated. The private key stays on the computer of the supplicant and remains unlnown to the certificate provider. The provide will be able to issue a certificate only after requesting and receiving the public key.

The most advanced method of code signing is know as "extended validation code signing certificates". This method is considered to be the most secured, since it deals with two of the most common loopholes exploited by the developers of malicious code - weak private key protection and poor process of identity verification.

The so-called extended validation implies the additional use of USB dongles that offer an advanced protection. However, it may not be very convenient to use such USB key within the company, since it may become lost when passed from one member to another. Also, it is not recommended to copy, clone, duplicate USB dongle or use any USB dongle emulators, as it's not a practice that falls on the right side of the manufacturers’ ToS. So, a much better option would be to share a **[USB certificate dongle over the network](https://www.flexihub.com/digital-signature-usb-dongle-sharing.html)**.

The most convenient and reliable way would be to use software like **[FlexiHub](https://www.flexihub.com/)**. It will make a digital certificate USB dongle available to everyone in the office, remaining in the same place all the time.

**How to use FlexiHub to get remote access to your digital certificate dongle**
===============================================================================

A couple of steps below will help you to get the idea of how to **[share a USB dongle](https://www.flexihub.com/share-usb-dongle.html)** over network:

1. Choose a subscription plan that best fits your needs. Register your FlexiHub account after that.

2. Install the software on the computer (server) with a connected USB key and the remote computer (client) that will access it remotely.

3. To share USB certificate dongle, start the software on both machines and log into your account using the same credentials.

4. In the app's interface on the client computer select the peripheral that you'd like to connect to and click "Connect". Now, you can manage the USB dongle as if it were attached to your computer physically.
