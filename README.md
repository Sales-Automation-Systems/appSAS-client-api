# Sales Automation Systems Client API

Real-time event tracking and webhook API documentation for Sales Automation Systems.

## 🚀 Overview

This repository contains the API documentation for the Sales Automation Systems Client API, built with [Scalar](https://github.com/scalar/scalar) - a modern, interactive API documentation tool.

## 📖 Documentation

View the live API documentation at: [https://appSAS-client-api.vercel.app](https://appSAS-client-api.vercel.app)

## 🔧 API Features

- **Real-time Event Tracking**: Track contact and company attribution events
- **Webhook Integration**: Configure webhooks to receive outbound lead data
- **RESTful Design**: Simple, intuitive API endpoints
- **Bearer Authentication**: Secure API key authentication

## 📡 API Endpoints

### Contact Attribution
```
POST /attribution/{client_id}/contact
```
Track individual contact actions and attribution data using email addresses.

### Company Attribution
```
POST /attribution/{client_id}/company
```
Track company-wide actions and attribution data using domain names.

## 🎯 Event Types

- `sign_up` - New user registration
- `meeting_booked` - Meeting scheduled
- `paying_customer` - Conversion to paying customer
- `website_visitor` - Website visit tracking
- `dnc` - Do not contact flag

## 🔑 Authentication

All API requests require a Bearer token:

```bash
Authorization: Bearer YOUR_API_KEY
```

Contact Sales Automation Systems to obtain your API key.

## 💻 Local Development

To run the documentation locally:

1. Clone the repository:
```bash
git clone https://github.com/Sales-Automation-Systems/appSAS-client-api.git
cd appSAS-client-api
```

2. Serve the files using any static file server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server

# Using PHP
php -S localhost:8000
```

3. Open http://localhost:8000 in your browser

## 📚 Resources

- [Setup Guide Video](https://www.loom.com/share/10142595493d4523be825e872d413f91?sid=e1ea2827-7cce-4318-a489-c3f34ca6f3fa)
- [HubSpot via Zapier Setup](https://www.loom.com/share/a489487de1844a54a6f318fb3ea23842?sid=dc22ac70-b823-401d-b9c0-b075b9dcdc90)
- [Sales Automation Systems Website](https://salesautomation.systems)

## 🏗️ Project Structure

```
appSAS-client-api/
├── index.html        # Scalar API reference UI
├── openapi.yaml      # OpenAPI 3.0 specification
├── favicon.svg       # SAS brand favicon
├── vercel.json       # Vercel deployment config
└── README.md         # This file
```

## 🚢 Deployment

This documentation is automatically deployed to Vercel on every push to the main branch.

To deploy your own instance:

1. Fork this repository
2. Import into Vercel: https://vercel.com/import
3. Deploy (no build configuration needed - it's a static site)

## 🛠️ Technologies

- **[Scalar](https://github.com/scalar/scalar)** - API documentation UI
- **OpenAPI 3.0** - API specification format
- **Vercel** - Hosting and deployment

## 📝 License

Copyright © 2025 Sales Automation Systems. All rights reserved.

## 📧 Support

For API support and questions, contact: support@salesautomation.systems

