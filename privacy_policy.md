# GroSquare Privacy Policy

**Last updated:** [28-09-2026]

This Privacy Policy explains how GroSquare ("the App", "we", "us") collects, uses, and
protects information when a shop and its staff use the App. GroSquare is a subscription
add-on for retail and distribution businesses that run TallyPrime; it is provided by GroSquare.

> **Before publishing:** replace every `[FILL IN ...]` placeholder below, then host this
> policy at a public URL — Google Play requires a live link, not a file in this repo.

## 1. Information we collect

### Account information
When your shop admin creates your login, we collect your **name, email address, shop
identifier, and role** (Admin, Manager, Salesperson, Accountant, or Purchase Manager) via
Firebase Authentication. This identifies you and determines what you can see and do in
the App.

### Business data synced from TallyPrime
Your shop's office computer runs a separate desktop sync service that reads data from your
own TallyPrime installation and publishes it to our cloud database, scoped to your shop
only. This includes:

- Customer/party ledgers and their outstanding balances
- Inventory and stock levels
- Sales and purchase invoices
- Payments and receipts

Any sales order or payment you create in the App while offline is queued on your device and
sent back into TallyPrime once your shop's sync service processes it. GroSquare never
connects to TallyPrime directly from your phone.

### Location data
With your permission, the App records your device's GPS location when you log a field visit
or create a sales order in the field, so your shop can see where visits happened. You can
decline location permission; visit-tracking features will not work without it.

### Camera and photos
The App may request camera or photo library access if you attach an image (for example, to
a visit or a document) — only when you choose to do so.

### Device and usage data
We use Firebase Analytics and Firebase App Check to understand feature usage, diagnose
crashes, and confirm requests come from a genuine, unmodified install of the App. This may
include device type, OS version, app version, and general usage events. We do not use this
data to identify you personally beyond your account.

### Biometric authentication
If you enable biometric unlock, your fingerprint/face data is processed entirely on your
device by its operating system. GroSquare never receives or stores biometric data.

## 2. How we use this information

- To authenticate you and enforce shop- and role-based access to your shop's data
- To sync sales orders, payments, and other records between the App and your shop's Tally
  data
- To provide field-visit tracking, if you enable location permission
- To operate, maintain, and improve the App, and to diagnose technical issues
- To communicate service-related notices (e.g., subscription status)

We do **not** sell your data, and we do not use your business data (customers, inventory,
invoices) for advertising.

## 3. Data storage and security

Data is stored in Google Firebase (Cloud Firestore, Firebase Authentication, Firebase
Storage), hosted in the `asia-south1` region. Access to your shop's data is restricted by
server-side security rules keyed to your account's shop and role — no shop can read another
shop's data, and no role can act outside its permissions. Local, on-device storage
(used for offline access) is cleared when you log out.

## 4. Data sharing

We share data only with:

- **Your own shop's staff and admin**, according to their role
- **Firebase/Google Cloud**, our infrastructure provider, to store and sync data
- Law enforcement or regulators, only if required by law

We do not share your data with third parties for their own marketing purposes.

## 5. Data retention

Business data (customers, inventory, invoices, payments) is retained for as long as your
shop's subscription is active, mirroring what exists in your own TallyPrime data. Account
data is retained until your account is removed by your shop admin. You may request deletion
of your account data by contacting [FILL IN SUPPORT EMAIL].

## 6. Your choices

- You can decline camera, location, or biometric permissions; only the related features will
  be unavailable.
- You can ask your shop admin to disable or remove your account at any time.
- You can request a copy of, or the deletion of, your personal account data by contacting us
  (see below).

## 7. Children's privacy

GroSquare is a business tool for shop staff and is not directed at, or knowingly used by,
children.

## 8. Changes to this policy

We may update this policy as the App changes. Material changes will be reflected in the
"Last updated" date above.

## 9. Contact us

Questions about this policy or your data: [grosquare.in@gmail.com]
