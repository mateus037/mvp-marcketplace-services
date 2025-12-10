# MVP Marketplace Services

Gateway service communicating with external providers.

## Tech Stack
- Node.js
- Express
- TypeScript

## External Services
- **FakeStoreAPI**: Product data
- **ViaCEP**: Address lookup

## Environment Setup
1. Configure the variables:
   - `PORT`: Port to run the server on (default: `3002`)
   - `FAKESTORE_URL`: Base URL for FakeStoreAPI
   - `VIACEP_URL`: Base URL for ViaCEP

## Running
```bash
npm install
npm run dev
```

## Docker
```bash
docker build -t mvp-marcketplace-services .
docker run -p 3002:3002 mvp-marcketplace-services
```
