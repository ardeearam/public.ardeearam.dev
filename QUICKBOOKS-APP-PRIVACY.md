# Privacy Policy

**Last updated: April 13, 2026**

This Privacy Policy describes how this application ("Application," "we," or "our") collects, uses, and protects information when you use it to connect to QuickBooks Online via the Intuit OAuth 2.0 API.

---

## 1. Who This Applies To

This Application is a private, internal tool used to access QuickBooks Online data on behalf of a single authorized user or organization. It is not a public-facing service and does not solicit or collect information from the general public.

---

## 2. Information We Access

When you authorize the Application, it may access the following types of data from your QuickBooks Online account, solely as directed by you:

- Company information (name, address, contact details)
- Financial records (invoices, payments, accounts, transactions)
- Customer and vendor information
- Other accounting data available through the QuickBooks Online Accounting API

The Application accesses this data only in response to explicit actions you take (e.g., running a query or creating a record). It does not perform background data collection or monitoring.

---

## 3. Information We Store

The Application stores the following on your local device only:

- **OAuth credentials** (access token, refresh token, client ID, client secret, realm ID) — stored in an AES-256-CBC encrypted file (`credentials.json.enc`) on your local machine
- **Encryption password** — never stored anywhere; you must provide it each time the Application runs

No data is stored on external servers, databases, or cloud services operated by the Developer.

---

## 4. How We Use Information

Information accessed from QuickBooks Online is used exclusively to:

- Fulfill the specific request you make (e.g., listing transactions, creating an invoice)
- Display results to you in your local environment

We do not use your QuickBooks data for analytics, advertising, profiling, training of machine learning models, or any purpose beyond what you explicitly request.

---

## 5. Information Sharing and Disclosure

We do not sell, rent, trade, or share your data with any third parties, except:

- **Intuit Inc.** — The Application communicates directly with Intuit's QuickBooks Online API (`quickbooks.api.intuit.com`) and OAuth servers (`oauth.platform.intuit.com`) to authenticate and retrieve data. This communication is governed by [Intuit's Privacy Policy](https://www.intuit.com/privacy/statement/).
- **Legal requirements** — We may disclose information if required to do so by law or in response to valid legal process.

---

## 6. Data Security

We take reasonable measures to protect your credentials and data:

- OAuth tokens are stored locally using AES-256-CBC encryption via OpenSSL
- The encryption password is never stored and must be provided at runtime
- All API communication with Intuit uses HTTPS (TLS)
- No credentials or financial data are transmitted to the Developer

You are responsible for securing your local device and your encryption password. If your password is lost, re-authentication is required and previously stored credentials become inaccessible.

---

## 7. Data Retention

The Application retains your encrypted credentials on your local device until you delete the `credentials.json.enc` file. QuickBooks data retrieved during a session is displayed in your terminal and is not persisted beyond the immediate response.

---

## 8. Third-Party Services

The Application integrates exclusively with **QuickBooks Online** (Intuit Inc.). We are not responsible for Intuit's data practices. Please review Intuit's Privacy Policy at [https://www.intuit.com/privacy/statement/](https://www.intuit.com/privacy/statement/) for details on how Intuit handles your data.

---

## 9. Children's Privacy

This Application is not intended for use by individuals under the age of 18. We do not knowingly collect any information from minors.

---

## 10. Your Rights

Depending on your jurisdiction, you may have rights regarding your personal data, including the right to access, correct, or delete it. Since all data is stored locally on your own device or within your QuickBooks Online account (controlled by Intuit), you can exercise these rights by:

- Deleting the local `credentials.json.enc` file to remove stored credentials
- Managing your QuickBooks data directly within your QuickBooks Online account
- Revoking the Application's access at any time via your Intuit account at [https://accounts.intuit.com](https://accounts.intuit.com)

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by an updated "Last updated" date at the top of this document. Continued use of the Application after changes constitutes acceptance of the revised policy.

---

## 12. Contact

If you have questions or concerns about this Privacy Policy or the Application's data practices, please contact the Developer.
