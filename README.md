# Privacy Policy — USB Disk Utility & Storage Suite

**Application:** USB Disk Utility & Storage Suite  
**Package Name:** `com.clustereddreams.usbdisk.app`  
**Developer:** Clustered Dreams  
**Effective Date:** August 24, 2026  
**Website:** https://jasonbridges.github.io/usb-disk-utility-privacy-policy/

---

## 1. Core Privacy Commitment (Zero Data Collection)
USB Disk Utility & Storage Suite is built with a strict **Zero Data Collection** architecture. We do not collect, store, sell, monetize, or transmit your personal data, disk files, or private information. All disk operations (partitioning, formatting, counterfeit scanning, ISO flashing, and file carving) execute **100% locally and offline on your device**.

---

## 2. Information We Do NOT Collect
* **No File or Storage Contents:** Your files, partition tables, photos, documents, and disk contents never leave your physical device.
* **No Account or Personal Information:** We do not require registration, login, names, email addresses, or phone numbers.
* **No Location Tracking:** We do not access, track, or store GPS or network location.
* **No Device Sensors or Media:** We do not access contacts, photos, microphone, or camera.
* **No Advertisements or Ad Trackers:** The application contains zero third-party advertisement SDKs and zero ad tracking libraries.

---

## 3. Local Permissions & Usage
* **USB Host Access (`android.hardware.usb.host`):** Required to communicate directly with attached USB OTG flash drives, SSDs, SD card readers, and mass storage devices via standard SCSI/BOT protocols. USB communication occurs strictly between Android and the physical drive.
* **Foreground Service (`FOREGROUND_SERVICE_DATA_SYNC`):** Used to prevent the Android operating system from terminating long-running disk operations (such as formatting, flashing ISO images, counterfeit scans, or file carving) while the phone screen is off or in the background.
* **Wake Lock:** Prevents the CPU from sleeping while an active write/erase operation is in progress, ensuring physical drive partitions are not corrupted by sudden interruptions.

---

## 4. Anonymous Crash Diagnostics
To diagnose unexpected crashes, SCSI protocol anomalies, and device compatibility issues across diverse Android hardware, the app may collect anonymous diagnostic information via Google Firebase Crashlytics:
* Device Model & OS Version (e.g. Pixel 10 Pro Fold, Android 17)
* Crash stack traces and technical exception codes
* Non-personal hardware IDs (e.g. USB Vendor ID and Product ID of connected card readers)

This diagnostic information contains no personally identifiable information (PII) and is used exclusively to maintain stability and resolve software bugs.

---

## 5. In-App Purchases & Billing
Optional Pro upgrades are processed directly and securely by **Google Play In-App Billing**. We never receive, process, or store your payment details, credit card numbers, or billing addresses.

---

## 6. GDPR & CCPA Compliance
Because the application does not collect, retain, or process personal data, no personal data records exist in our systems. Users maintain full sovereignty and control over their physical hardware and data.

---

## 7. Contact Us
For any questions regarding this Privacy Policy or application security:
* **Developer:** Clustered Dreams
* **Email:** support@clustereddreams.com
* **Repository:** https://github.com/jasonbridges/usb_disk_utility_android
