# Privacy Policy for HyperStat

**Effective Date:** March 9, 2026

Thank you for choosing to be part of our community at HyperStat. We are committed to protecting your personal information and your right to privacy.

### 1. Information We Collect
HyperStat is designed to be a local system performance monitor. **We do not collect, store, or share any personal data.** 

All hardware diagnostics, system statistics (CPU, RAM, Battery, Network, Storage), and device information are accessed strictly locally on your device in real-time. 

**Standard Hardware Metrics:** Core system metrics such as CPU usage, RAM allocation, Battery levels, Network speed, and Storage capacity are queried directly from standard open Android APIs and Linux system files provided by the operating system. If a device manufacturer restricts access to any of these standard data points, HyperStat will either display the metric as unavailable or utilize safe fallback logic to approximate the value based on remaining available system data.

**Note on Custom Hardware Estimations:** Due to standard Android API restrictions, many device manufacturers block direct access to GPU hardware sensors (which normally results in an empty or 0% reading). To overcome this, HyperStat utilizes an independent, custom software algorithm to approximate **GPU Load** based on other available system heuristics and memory bandwidth. Additionally, metrics like **Frametime and FPS** are derived from the system's current display refresh rate rather than direct graphics pipeline polling. This ensures you still receive performance insights even when direct API access is restricted.

### 2. Permissions & Usage
To function properly, HyperStat requests the following permissions:
- **Display Over Other Apps (Overlay):** Used exclusively to render a floating performance widget on top of other applications or games. The sole function of this overlay is to provide real-time, on-screen hardware statistics to the user (specifically displaying: Network speed, Frametime, FPS, CPU Load/Temperature, RAM Usage, GPU Load, and Battery Level). It does not interact with, record, or capture the screen content of the underlying apps.
- **Location (Fine):** On older versions of Android, this permission is strictly required by the Android operating system to read the name of the currently connected Wi-Fi SSID network. We **never** track, store, or send your physical location data.
- **Storage/Media:** Used to calculate and display the total and available storage space on your device. We do not read or access your personal files or photos.

### 3. Third-Party Services (Analytics)
We use **Google Firebase Analytics/Crashlytics** strictly to collect anonymous crash reports and basic app usage metrics to help us fix bugs and improve stability. 
This data is completely anonymous and contains no personal identifiers. 

### 4. Children's Privacy
Our application does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children.

### 5. Trademark & Affiliation Disclaimer
**"HyperStat" is an independent system monitoring and diagnostics app. It is NOT affiliated, associated, authorized, endorsed by, or in any way officially connected with any other companies, products, services, or registered trademarks.**
This application is a standalone software utility developed solely for Android devices.

### 6. Limitation of Liability
The App is provided "AS IS". The developer is not liable for any damages, battery impact, or data loss resulting from use.

### 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. You are advised to review this page periodically for any changes.

### 8. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact the developer via the official Google Play Store listing.
