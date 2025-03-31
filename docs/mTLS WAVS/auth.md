---
id: authentication
title: Authentication
sidebar_position: 2
---

# Authentication

To access the FundingShield WAVS API, users must authenticate their requests using an API key and client certificate.

## API Key

Include the API key in the `Ocp-Apim-Subscription-Key` header for every request.

### Example:
```plaintext
Ocp-Apim-Subscription-Key: YOUR_API_KEY
```

## Rate Limits:
API requests are rate-limited. Ensure you adhere to the service limits specified in your contract.
