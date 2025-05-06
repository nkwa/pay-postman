# Nkwa Pay API - Postman Collection

A Postman collection for the Nkwa Pay API, allowing you to easily integrate mobile money payments across your applications.

## Overview

This repository contains ready-to-use Postman collection for testing and interacting with the Nkwa Pay API. The collection includes all endpoints for collections, disbursements, payment status checks, and service availability monitoring.

## Collection Contents

The collection includes the following API endpoints:

- **Get Payment** - Retrieve details of an existing payment by ID
- **Collect Payment** - Request money from a mobile money account
- **Disburse Payment** - Send money to a mobile money account
- **Check Availability** - Verify which operators and operations are currently available

## Getting Started

### Prerequisites

- [Postman](https://www.postman.com/downloads/) installed on your machine
- Nkwa Pay API key (contact Nkwa for access)

### Installation

1. Clone this repository or download the collection file:
   ```bash
   git clone https://github.com/nkwa/pay-postman.git
   ```

2. Import the collection into Postman:
   - Open Postman
   - Click "Import" button
   - Select the `collections.json` file

3. Set up environment variables:
   - Create a new environment in Postman
   - Add the following variables:
     - `baseUrl`: Set to `https://api.pay.staging.mynkwa.com` for testing
     - `apiKey`: Your Nkwa Pay API key

### Usage

1. Select the imported collection in Postman
2. Choose the environment with your variables
3. Begin making API requests:
   - To collect payments, use the "Collect Payment" endpoint
   - To disburse funds, use the "Disburse Payment" endpoint
   - To check payment status, use the "Get Payment" endpoint
   - To verify service availability, use the "Check Availability" endpoint

## API Documentation

For complete API documentation, visit:
- [Nkwa API Documentation](https://docs.mynkwa.com/api-reference)

## Reference

This collection was generated from the Nkwa Pay OpenAPI specification on April 22, 2025.

## Support

For support with the API, please contact Nkwa support.
