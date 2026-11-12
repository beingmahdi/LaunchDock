# Privacy Policy for LaunchDock

**Last updated:** November 13, 2026

Thank you for choosing **LaunchDock** ("we", "our", or "the application"). We respect your privacy and are committed to protecting it. This Privacy Policy explains our practices regarding data collection, usage, and storage when you use LaunchDock.

---

### 1. No Collection of Personal Information
LaunchDock is designed as an offline-first Windows utility. **We do not collect, transmit, sell, or share any personal information, telemetry, analytics, or behavioral tracking data.**

### 2. Local Data Storage
All data required for LaunchDock to function is stored strictly locally on your computer (in your local application data directory):
* **Custom Shortcuts & Apps**: File paths, display names, and base64-encoded application icons for items you add to your dock.
* **User Preferences**: UI configuration settings such as themes, window opacity, panel width, icon dimensions, animation speed, and auto-start preferences.

This data never leaves your device and is only accessible by the LaunchDock application on your machine.

### 3. Network Connections & Automatic Updates
LaunchDock only establishes an outgoing internet connection for one purpose:
* **Checking for Software Updates**: The application periodically queries the public GitHub Releases API (`https://api.github.com` and `https://github.com/beingmahdi/LaunchDock`) to check whether a newer version of LaunchDock is available.
* During this update check, only standard technical HTTP request headers (such as your IP address, which is inherent to any internet connection) are processed by GitHub according to GitHub's standard privacy policies. No personal information or application data is transmitted.
* Downloads of update packages only occur when initiated by you or authorized via the application settings.

### 4. Third-Party Services
LaunchDock does not integrate any third-party tracking services, advertising networks, or analytics SDKs.

### 5. Data Security & Permissions
* **File System Access**: LaunchDock reads local file shortcuts (`.lnk` files), executables (`.exe`), and folder paths solely to display icons and launch applications when clicked by the user.
* **Auto-Start**: If enabled by the user in Settings, LaunchDock creates a standard Windows registry entry to start minimized with Windows.

### 6. Children's Privacy
LaunchDock does not collect any data from anyone, including children under the age of 13.

### 7. Changes to This Privacy Policy
We may update this Privacy Policy from time to time. Any changes will be posted to this page with an updated "Last updated" date.

### 8. Contact Us
If you have any questions or feedback regarding this Privacy Policy, please contact us:
* **Developer**: Mahdi Hasan (Colonelx)
* **GitHub Repository**: [https://github.com/beingmahdi/LaunchDock](https://github.com/beingmahdi/LaunchDock)
* **Issues / Inquiries**: [https://github.com/beingmahdi/LaunchDock/issues](https://github.com/beingmahdi/LaunchDock/issues)
