
# Cohere API Proxy
vercel-cohere-api

A simple proxy service for Cohere API using Vercel Edge Functions.

## Features

- ✅ Edge runtime for better performance
- ✅ Automatic request forwarding
- ✅ CORS support
- ✅ Error handling

## Usage

After deployment, replace `api.cohere.com` with your Vercel domain:

```bash
# Original
curl https://api.cohere.com/v1/models

# Through proxy
curl https://your-proxy.vercel.app/v1/models

