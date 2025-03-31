---
id: example-postman-configuration
title: Example Configuration in Postman
sidebar_label: Configure Certificates
sidebar_position: 5
---

# Example Configuration in Postman

Follow these steps to configure certificates in Postman:

## Steps to Configure Certificates

1. Open Postman and navigate to **Settings** > **Certificates**.
2. Click **Add Certificate** and provide the following details:
   - **Host:** Enter the base URL (e.g., `{{baseUrl}}`).
   - **PFX File:** Upload your `.pfx` certificate file.
   - **Passphrase:** Enter the password for your certificate.

3. Save the configuration.
4. Restart Postman if necessary.

---

:::important
"Reminder: Your certificate is valuable. Store them in a safe and secure location."
:::

This configuration ensures that your requests are authenticated securely using the provided certificate.
