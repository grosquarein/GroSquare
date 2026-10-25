# GroSquare Privacy Policy

**Effective date:** 25 October 2026
**Last updated:** 25 October 2026

This Privacy Policy explains how GroSquare ("the App", "we", "us") collects, uses, shares and
protects information when a shop and its staff use the GroSquare mobile app, the GroSquare Desk
Windows app, and the GroSquare desktop connection app (together, "the App"). GroSquare is a
subscription add-on for retail and distribution businesses that run TallyPrime. It is provided
by Saneesh, trading as GroSquare, India. You can reach us at **grosquare.in@gmail.com**.

## 1. Who decides what

- **Your account data** (your login, name, role) — we decide how it is used, as described here.
- **Your shop's business records** (customers, suppliers, stock, invoices, payments, orders,
  visits — including details of your shop's own customers and suppliers) — your shop decides
  what goes in; we store and process them on your shop's behalf to run the service. For the
  personal data of your shop's customers and suppliers, your shop is the Data Fiduciary and
  GroSquare acts as its Data Processor under the Digital Personal Data Protection Act, 2023.

## 2. Information we collect

### Account information
When a shop owner signs up, we collect the **shop name, shop phone number, and the owner's email
address**. When a shop Admin adds staff, we collect each person's **email address, display name,
and role(s)** (Admin, Manager, Salesperson, Accountant, Purchase Manager). Logins are handled by
Firebase Authentication; passwords are never visible to us or to your shop.

### Business data synced from TallyPrime
The shop's office PC runs the GroSquare desktop app, which reads from the shop's own TallyPrime
and publishes to our cloud database, scoped to that shop only: customer and supplier ledgers
(names, addresses, phone numbers, email, GSTIN/PAN where Tally holds them) and their balances,
stock items and stock levels, vouchers (sales, purchase, receipts, payments and others),
outstanding bills, the chart of accounts, ledgers and budgets, and the company's letterhead and
bank details.

Invoices, receipts, orders, sales returns and new customers created in the App are queued in the
cloud and written into TallyPrime by the shop's desktop app. The App never connects to
TallyPrime directly.

### Data you create in the App
Quotations, field visits (check-in/check-out), notes, and the shop's printed-invoice details are
stored in the cloud for your shop.

### Location (mobile app only)
With your permission, the mobile app records your device's GPS position when you check in or out
of a field visit, record a payment, or create an order or return, so your shop can see where it
happened. Permission is asked only when you open one of those screens. You can decline; the
visit features need it, and the other entries are saved without a location. The Windows app does
not collect location.

### Camera and photos
If you choose to attach a photo (a visit photo, a payment proof, or an order attachment), the App
uses the camera or photo library (on Windows, a file you pick) and uploads that photo to your
shop's cloud storage, where your shop's users can see it.

### Device and usage data
We use **Firebase Analytics** to understand feature usage and diagnose problems (device type, OS
version, app version, general usage events), **Firebase App Check** to confirm requests come from
a genuine install, and **Firebase Remote Config** to tell an outdated App to update. We do not
use these to identify you beyond your account.

### Biometric authentication
If you enable biometric unlock on your phone, your fingerprint or face is checked entirely by
your device's operating system. GroSquare never receives or stores biometric data.

### Desktop app
The desktop app stores its own sign-in for your shop on the PC, encrypted with Windows' per-user
protection, and keeps local logs (which can include data read from Tally) on that PC.

## 3. How we use this information

- To sign you in and enforce shop- and role-based access to your shop's data
- To sync records between TallyPrime and the App, and write the App's entries into Tally
- To provide field-visit tracking and reminders (reminders are created on your device)
- To bill the shop's subscription
- To send service emails (for example, the desktop-app setup email after signup)
- To keep a security record of administrative actions (see Section 6)
- To operate, secure, maintain and improve the service and diagnose problems

We do **not** sell your data, and we do not use your shop's business data for advertising.

## 4. Security and access control

Every read and write is checked by server-side security rules tied to your account's membership
in your shop. **No shop can read or change another shop's data**, and a removed or disabled
user loses access on their next request.

Within a shop, access also depends on role:

- **Enforced on the server:** what each role may *write* (for example, only a Salesperson,
  Manager or Admin can create invoices, orders and receipts; only an Admin manages staff); and
  who may *read* customers, suppliers, quotations, the accounting reports (ledgers, chart of
  accounts, budgets), the staff list and the security log.
- **Visible to every user of the shop:** stock, invoices, outstanding bills, the queue of entries
  waiting for Tally, sync status and field visits — the App's home and dashboard screens use
  them for every role. Some finer per-screen restrictions are applied by the App itself rather
  than the server.

Data is encrypted in transit. On-device copies kept for offline use are deleted when you log
out; the App warns you first if something you entered has not uploaded yet.

## 5. Where data is stored and who processes it

We use the following service providers. Each receives only what it needs for its purpose.

| Provider | What for | Data involved |
|---|---|---|
| **Google Firebase / Google Cloud** (Authentication, Cloud Firestore, Cloud Storage, Cloud Functions, Analytics, App Check, Remote Config) | Logins, the shop database, photo storage, server functions, usage analytics, install checks, update checks | Everything described in Section 2. Cloud Firestore and Cloud Functions run in Google Cloud's `asia-south1` (Mumbai, India) region. |
| **Cashfree Payments** | Taking the subscription payment | Shop ID, shop phone number, order amount. Card/UPI/bank details are entered on Cashfree's checkout and never reach us. |
| **Google (Gmail), via SMTP** | Sending service emails | The recipient's email address, shop name and shop ID |
| **Google Maps Platform** | The territory map (mobile app) | Map requests from your device; customer positions shown on the map come from your shop's visit check-ins |
| **Google Play services** | App Check (Play Integrity) and app updates on Android | Device and app integrity signals |
| **GitHub** | Hosting the desktop installer download and this policy | Only what any website visit involves |

When you choose to share an invoice or message through WhatsApp, email or another app on your
device, that app's own privacy policy applies to what you send. Thermal receipt printing happens
over Bluetooth between your phone and printer only.

We may also disclose data where required by law or by a lawful order of a competent authority.

## 6. Retention

| Data | Kept for |
|---|---|
| Sync status log | About 30 days, then deleted automatically |
| Security audit log (staff added, roles changed, users disabled/enabled, PCs linked/unlinked, failed entries retried) | About 1 year, then deleted automatically |
| Business data mirrored from Tally | While the shop's account exists; refreshed from Tally on each sync |
| Entries queued for Tally, quotations, visits, photos | While the shop's account exists |
| Account data (login, staff-list entry) | Until the account is deleted (Section 7) or the shop's account is closed |
| Subscription payment records | As long as Indian tax and accounting law requires us to keep billing records |
| Firebase Analytics data | For the retention period set in Firebase Analytics (no longer than 14 months) |

Automatic deletions are carried out by the database's expiry policy and normally happen within a
day or two of the date shown. Your shop's records **inside TallyPrime** are on your own PC and are
never deleted or changed by GroSquare except by the entries your shop creates in the App.

## 7. Your rights

Under the Digital Personal Data Protection Act, 2023 you may:

- **Access** a summary of the personal data we process about you and how we process it
- **Correct, complete or update** it
- **Erase** it, where it is no longer needed for the purpose it was collected for, or where you
  withdraw consent, unless the law requires us to keep it
- **Withdraw consent** for processing that relies on consent — this does not affect processing
  already done
- **Nominate** another person to exercise these rights if you die or become unable to
- **Have a grievance redressed** (Section 8), and then, if unresolved, complain to the Data
  Protection Board of India

**Deleting your account:** open the App → **Settings → Delete my account**, which explains what
is deleted and what stays and sends us a request. You can also email **grosquare.in@gmail.com**.
Your login, your staff-list entry and your login's link to the shop are deleted. Records you
created for the shop (invoices, receipts, orders, quotations, visits) are the shop's business
records and stay with the shop, and anything already in TallyPrime stays in Tally. A shop owner
can ask for the whole shop's cloud data to be deleted or exported. We will act on a request
within 30 days.

Staff can also ask their shop Admin to disable or remove their access at any time.

## 8. Grievance Officer

- **Name:** Saneesh
- **Email:** grosquare.in@gmail.com
- **Response time:** we acknowledge grievances within 7 days and resolve them within 30 days.

## 9. Contact

Questions about this policy or your data, and data requests: **grosquare.in@gmail.com**

## 10. Children

GroSquare is a business tool for shop owners and staff. It is not directed at children, and we
do not knowingly process children's personal data.

## 11. Changes to this policy

We may update this policy as the service changes. Changes are reflected in the dates at the top.
