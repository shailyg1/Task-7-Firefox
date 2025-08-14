#  Task 7: Browser Extension Audit

##  Objective
To audit Firefox browser extensions, identify any untrusted or suspicious add-ons, and maintain a clean and secure browsing environment.

---

##  Tools Used
- **Mozilla Firefox** (Extensions Manager)
- **Manual Extension Review** via Firefox Add-ons page

---

##  Steps Performed

### 1️⃣ Checked Installed Extensions
Opened `Menu → Add-ons and Themes → Extensions` and reviewed installed extensions.

### 2️⃣ Collected Extension Details

#### 1. **OneTab**
- **Version:** 1.79 (replace with actual version)
- **Permissions:**
  - Access browser tabs
  - Read & modify browsing history
  - Store and retrieve tab lists
- **Source:** [Mozilla Add-ons Store](https://addons.mozilla.org/en-US/firefox/addon/onetab/)
- **Risk Level:** ✅ Safe (Verified by Mozilla)
- **Purpose:** Helps declutter browser by converting all open tabs into a single list to save memory and reduce CPU usage.

#### 2. **Dark Reader**
- **Version:** 4.9.82 (replace with actual version)
- **Permissions:**
  - Access your data for all websites
  - Modify the appearance of websites
  - Read browsing history
- **Source:** [Mozilla Add-ons Store](https://addons.mozilla.org/en-US/firefox/addon/darkreader/)
- **Risk Level:** ✅ Safe (Verified by Mozilla)
- **Purpose:** Applies dark mode to websites, reducing eye strain during prolonged browsing.

---

### 3️⃣ Identified Suspicious Extensions
No suspicious or malicious extensions were detected.  
All installed extensions are from the official Mozilla Add-ons Store and have been verified.

---

### 4️⃣ Security Recommendations
-✅ Install extensions only from the **official Mozilla Add-ons Store**.
  Review installed extensions **monthly** and remove unused ones.
- Always check permissions requested by an extension.
-  Avoid extensions from unknown developers or unverified sources.

---

##  Screenshots
- **Before Audit:** `screenshot_before.png` — showing OneTab & Dark Reader installed.
- **After Audit:** `screenshot_after.png` — showing the final safe extension list.

---

##  Files in Repository
- `README.md` — Detailed explanation and steps
- `extensions_inventory.txt` — List of installed extensions with details
- `suspicious_extensions.txt` — List of suspicious/untrusted extensions (empty in this case)
- `screenshot_before.png` — Extensions list before audit
- `screenshot_after.png` — Extensions list after audit

---

##  Outcome
The Firefox browser was found to have **2 safe extensions** — **OneTab** and **Dark Reader** — both verified by Mozilla and serving legitimate purposes.  
No suspicious extensions were found, and browser security best practices were followed.
