# TxCapture Privacy Policy

## 1. Introduction
TxCapture is a user-initiated UI automation recorder designed for enterprise testing and workflow automation teams.

This Privacy Policy explains what information TxCapture collects, how it is used, and how your privacy is protected when using the Microsoft Edge extension.

TxCapture complies with the Microsoft Edge Web Store User Data Policy, including the Limited Use requirements.

---

## 2. Information We Collect (During Active Capture Only)
TxCapture collects only non-personal, non-identifying interaction metadata, and **only when the user explicitly clicks "Start Capture."**

This may include:
- Page title
- HTML element selector metadata (for example, attributes used for UI automation)
- Event types such as click, input, or change
- Structured metadata required to generate automation output (for example, XAML)

This temporary metadata is necessary solely to fulfill the extension’s purpose:  
**generating automation-ready output from user-initiated UI interactions.**

---

## 3. Information We Do NOT Collect
TxCapture does **not** collect, access, store, or transmit:
- Names or identity data
- Passwords, credentials, or form values
- Cookies
- Session tokens
- Keystrokes
- Browsing history
- Personal or sensitive user information

TxCapture does not monitor pages in the background and does not track user behavior.

---

## 4. How Information Is Used
Only during an active capture session:
- Temporary metadata is used to generate automation output (such as XAML)
- The generated output is downloaded locally to the user’s machine

Captured information is **not** used for:
- Analytics
- Advertising
- Profiling
- Data sharing

If a backend API is configured, metadata is transmitted securely over TLS to an enterprise-controlled backend **solely for the purpose of generating the automation file**.  
No data is retained on the server after processing.

---

## 5. Data Retention
TxCapture follows a strict non-retention model:
- No data is stored after a capture session ends
- Temporary in-session metadata is cleared when the user clicks **Stop Capture**
- No long-term storage occurs in the extension, cloud, or backend

---

## 6. Data Sharing and Disclosure
TxCapture does not:
- Share data with third parties
- Sell data
- Use data for advertising or analytics
- Send data to external services other than an enterprise’s own backend (if configured)

---

## 7. Permissions Usage
TxCapture requests only the minimum permissions required:
- **activeTab** — to access the active page during recording only
- **scripting** — to inject capture scripts only when the user starts capture
- **storage** — for temporary in-session metadata

No background monitoring, host-wide access, cookies, or browsing history permissions are used.

---

## 8. User Controls
Users maintain full control:
- Recording begins only when the user clicks **Start Capture**
- Recording stops immediately when the user clicks **Stop Capture**
- No passive data collection occurs at any time

---

## 9. Security
- All optional backend communications use TLS 1.2 or TLS 1.3
- No sensitive or identifying information is collected or transmitted
- Metadata is processed in-flight and discarded after use

---

## 10. Contact Information
For questions about this Privacy Policy or enterprise deployments, contact your TxCapture administrator or your TestingXperts representative.
