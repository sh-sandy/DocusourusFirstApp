---
id: curl-example
title: Example cURL Request
description: A guide on how to make a cURL request using a certificate.
sidebar_position: 6
---

## Example cURL Request with Certificate

To make a cURL request using a certificate, you can use the following command:

```plaintext
curl -X GET "https://apim-fundingshield-prod-eastus2-01.azure-api.net/cert-wavs/wavs" \
    --cert client-cert.pem \
    --key client-key.pem \
    -H "Ocp-Apim-Subscription-Key: YOUR_API_KEY"
```

## Search WAVS Requests API

### Endpoint

```plaintext
GET https://apim-fundingshield-prod-eastus2-01.azure-api.net/cert-wavs/wavs?searchString=<string>&skip=<integer>&limit=<integer>
