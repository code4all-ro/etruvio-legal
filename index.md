# Privacy Policy — etruvio

**Last updated:** 2026-05-07
**Effective date:** 2026-05-07

This Privacy Policy describes how **CODE4ALL SRL** ("we", "us", or "etruvio") collects, uses, and protects personal data when you use the **etruvio** mobile application (the "App") and the related family-oriented digital-wellbeing service.

We are based in Romania and process personal data in accordance with the EU General Data Protection Regulation (GDPR), Romanian Law 190/2018, and applicable children's privacy rules.

---

## 1. Who we are

**Data controller:** CODE4ALL SRL
**CUI / VAT:** RO44417884
**Trade Register:** J2021000917152
**Registered address:** Str. Stejarului 128 F, Sat Ulmi, jud. Dâmbovița, cod poștal 137455, Romania
**Email:** developer@code4all.ro
**Website:** https://etruvio.ro

If you have any question about this policy or want to exercise your rights, contact us at the email above.

---

## 2. Who uses etruvio

etruvio is a **family-oriented digital-wellbeing service**. There are two categories of users:

- **Parents (account holders)** — adults who create an account, manage one or more children, and configure rules.
- **Children** — minors whose devices are managed by a parent. Children do not create their own account; they receive a child profile that is created and controlled by their parent.

The App is **not directed to children under 16 acting on their own behalf**. Children only use the App through a profile set up and supervised by a parent or legal guardian.

---

## 3. What data we collect

### 3.1 From parents

When a parent creates an account or uses the App, we process:

- **Account data:** email address, password (stored hashed by our authentication provider), display name, avatar (optional)
- **Authentication tokens** (sessions)
- **Household data:** the household name, settings, and preferences you configure
- **Device pairing data:** identifiers of devices you link to the household
- **Communication:** messages you send to support

### 3.2 From children (entered by the parent)

For each child profile, the parent provides:

- First name (or nickname)
- Date of birth or age
- Avatar (optional)
- Schedule, screen-time limits, and rules configured by the parent

### 3.3 From the child's managed device

When etruvio is installed on a child's Android device, we process:

- **App usage data** (which apps are running in the foreground and for how long), used **only** to enforce the rules set by the parent — for example to block a restricted app or to count screen time. This is collected via Android's `PACKAGE_USAGE_STATS` permission.
- **List of installed apps**, used so the parent can choose which apps to allow or restrict (`QUERY_ALL_PACKAGES`).
- **Pairing codes** scanned via the device camera (see §3.4).
- **Device identifier:** the `ANDROID_ID` value provided by the operating system (a per-app, per-device identifier scoped to etruvio; on Android 8 and later it changes between different apps). We use it to recognise the same device across pairing flows so a parent does not accidentally re-pair the same device twice.
- **Device information:** manufacturer, model, platform name ("Android"), and OS version, sent at pairing time so the parent can tell their children's devices apart in the dashboard.
- We do **not** collect the **Advertising ID**, **IMEI**, **MAC address**, **IMSI**, or the **hardware serial number**.
- **Diagnostic data** strictly necessary for the service: timestamps of rule events, error logs (no message content).

We do **not** access:
- Photos, videos, or files on the device
- Contacts, calendar, or SMS / call logs
- Microphone or audio
- Precise location (GPS)
- Browser history or web content
- The content of messages or notifications inside other apps

### 3.4 Camera

The App requests camera access **only** to scan a QR code when pairing a child's device with the parent's household. The camera frames are processed locally on the device by Google ML Kit (on-device, offline) and are **never** uploaded, recorded, or stored.

### 3.5 Accessibility service

The App declares an Android Accessibility Service. It is used **exclusively** to detect when a restricted app comes to the foreground so etruvio can show the block screen and enforce parent-configured rules. The service does **not** read on-screen text, capture form input, copy clipboard content, or transmit any accessibility events to our servers.

### 3.6 System overlay

The App requests permission to display content over other apps (`SYSTEM_ALERT_WINDOW`) **only** to show the block screen when a restricted app is opened. No advertising or content unrelated to the digital-wellbeing rules configured by the parent is shown.

### 3.7 All sensitive permissions are explicit opt-in

The permissions described in §3.3 – §3.6 — **Usage Access** (`PACKAGE_USAGE_STATS`), **Accessibility Service**, **Display over other apps** (`SYSTEM_ALERT_WINDOW`), and **Camera** — are all considered "special" or "runtime" permissions on Android. None of them is granted silently when the App is installed. For each one, the parent must:

1. Open the App on the child's device,
2. Tap the on-screen prompt explaining what the permission is for and why etruvio needs it,
3. Be redirected to the corresponding Android Settings screen, and
4. Manually enable the permission for etruvio.

The parent can revoke any of these permissions at any time from the same Android Settings screens. When a permission is revoked, the related feature stops working, but no other personal data is affected.

---

## 4. How we use the data

We use the data above only to:

1. **Provide the service** — create accounts, link devices, enforce rules, calculate screen time, deliver tasks and rewards configured by the parent.
2. **Secure the service** — detect abuse, prevent unauthorised access, audit administrative actions.
3. **Support** — answer your questions when you contact us.
4. **Comply with the law** — respond to legitimate legal requests.

We do **not** use personal data for advertising, profiling for marketing, or sale to third parties.

---

## 5. Legal bases (GDPR Art. 6 / 8)

| Purpose | Legal basis |
|---|---|
| Providing the service to the parent | Contract (Art. 6(1)(b)) |
| Processing children's data on behalf of the parent | Parental authority and consent (Art. 6(1)(a) / Art. 8) |
| Securing accounts and detecting abuse | Legitimate interest (Art. 6(1)(f)) |
| Legal obligations | Art. 6(1)(c) |

The **parent** is responsible for verifying that they have parental authority over the child whose profile they create.

---

## 6. Sharing and processors

We do not sell or rent personal data. We share data only with the following processors, each bound by a Data Processing Agreement:

| Processor | Purpose | Hosting region |
|---|---|---|
| **Supabase** (Supabase Inc. / Supabase Ireland) | Authentication, database, edge functions, realtime channels | Switzerland — Zurich (Central Europe) |
| **Google Play Services** | App distribution, in-app updates, integrity checks | EU / global |
| **Hostinger** (Hostinger International Ltd.) | Website hosting, deep-link verification | EU |

We do not currently use third-party analytics, advertising SDKs, or crash-reporting services.

---

## 7. International transfers

Some of the data we process is stored on servers located in **Switzerland** (operated by Supabase). Switzerland is not a member of the European Economic Area, but the European Commission has issued an **adequacy decision** for Switzerland (Commission Implementing Decision (EU) 2024/2493, renewing the prior decision), which means personal data can be transferred there under the same level of protection guaranteed inside the EEA, without additional safeguards.

For any other transfer of personal data outside the European Economic Area, we rely on the EU Standard Contractual Clauses (Commission Implementing Decision (EU) 2021/914) and additional safeguards as required by the GDPR.

---

## 8. Retention

| Data | Retention |
|---|---|
| Household data (children profiles, rules, screen-time history) | Until the parent deletes the household from the App, then erased immediately |
| Parent account (email, login credentials) | Until the parent requests account deletion by email; erased within 30 days of the request |
| Children profiles | Erased automatically when the parent deletes the household or the account |
| Screen-time and usage events | Up to 12 months on a rolling window, then aggregated or deleted |
| Authentication logs | Up to 12 months |
| Support messages | Up to 24 months |
| Backups | Encrypted, rotated within 30 days |

You can request earlier deletion at any time (see §10).

---

## 9. Security

We protect data through:

- HTTPS/TLS for all client-server traffic
- Encryption at rest (managed by Supabase)
- Row-Level Security policies on the database
- Separate credentials for parent and child sessions
- Restricted access to production systems on a need-to-know basis

No system is perfectly secure. If we become aware of a personal-data breach affecting you, we will notify you and the competent supervisory authority as required by law.

---

## 10. Your rights

Under the GDPR you (and, for a child, the parent on their behalf) have the right to:

- **Access** the personal data we hold about you
- **Rectify** inaccurate data
- **Erase** ("right to be forgotten")
- **Restrict** or **object to** processing
- **Portability** — receive your data in a structured, machine-readable format
- **Withdraw consent** at any time, where processing is based on consent
- **Lodge a complaint** with the Romanian Data Protection Authority (ANSPDCP, https://www.dataprotection.ro/)

To exercise any of these rights, email us at **developer@code4all.ro**. We respond within 30 days.

You can delete your household and all the data inside it directly in the App: **Settings → Delete household**. To delete the account itself (your email and login credentials) please contact us at **developer@code4all.ro** and we will erase it within 30 days.

---

## 11. Children's privacy

etruvio is designed to be operated by a parent who has authority over the child whose data is processed.

- We never display advertising to children.
- We never use children's data for marketing or profiling.
- The parent can review, modify, and delete the child profile at any time from the App.
- A child's data is automatically deleted when the parent deletes the child profile or the parent's account.

If you believe a child profile has been created in our service without parental consent, contact **developer@code4all.ro** and we will investigate and delete it.

---

## 12. Permissions on Android — plain-English summary

| Permission | Why etruvio needs it | What we never do |
|---|---|---|
| Camera | Scan a QR code to pair a child's device | Take photos, record video, upload images |
| Usage access (`PACKAGE_USAGE_STATS`) | Detect which app is in the foreground to enforce rules | Read app content, browser history, messages |
| Query installed apps | Let the parent pick which apps to restrict | Send the list of your apps to anyone besides our server, in encrypted form, for the parent's view |
| Display over other apps | Show the block screen when a restricted app is opened | Display ads or content unrelated to the family digital-wellbeing rules |
| Accessibility service | Detect a restricted app coming to the foreground | Read text on screen, capture input, log keystrokes |
| Foreground service & notifications | Keep the rules running and inform the user | Send marketing notifications |
| Run on boot | Re-enable rules after the device restarts | Wake the device for any other reason |

---

## 13. Changes to this policy

If we change this policy materially, we will notify users in the App and via the email associated with the parent account at least 14 days before the change takes effect.

---

## 14. Contact

CODE4ALL SRL
Str. Stejarului 128 F, Sat Ulmi, jud. Dâmbovița, cod poștal 137455, Romania
**developer@code4all.ro**
https://etruvio.ro
