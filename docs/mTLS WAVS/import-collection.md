---
id: import-collection
title: How to Import a Collection
sidebar_position: 4
---

# How to Import a Postman Collection

This guide explains how to import a collection in Postman using the app, web interface, or API.

## In Postman App

1. Open Postman on your computer.
2. Click on **Import** (found at the top left corner).
3. Choose the file type:
   - If you have a Postman Collection JSON file, click **Upload Files** and select your collection.
   - If you have a URL, paste it under **Link** and click **Continue**.
4. Click **Import**, and your collection will appear in the sidebar under **Collections**.

---

## In Postman Web App

1. Open [Postman Web](https://web.postman.co).
2. Click **Import** (top left corner).
3. Upload your JSON file or paste the collection URL.
4. Click **Import** to load the collection.

---

## Via Postman API

You can also programmatically import collections if you have a Postman API key.

### Steps:

1. Generate a Postman API key from your account settings.
2. Use the following `cURL` command to import your collection:

```bash
curl --location --request POST 'https://api.getpostman.com/collections' \
--header 'X-Api-Key: YOUR_POSTMAN_API_KEY' \
--header 'Content-Type: application/json' \
--data '@collection.json'
```

