# WhiteIntel API (BETA VERSION)

Welcome to the WhiteIntel API repository! This repository provides the necessary information and resources to use the WhiteIntel API, which is designed for enterprise-level subscriptions to access data on WhiteIntel.

whiteintel.io

## Overview

The WhiteIntel API offers a variety of endpoints to interact with the WhiteIntel platform. It is currently available only for enterprise-level subscriptions and has specific usage limits:

- **Daily Limit**: 500 API calls per day.
- **Rate Limit**: 2 seconds between each API call.
- **Password Information**: Requires verification of the target domain via the regular web UI. (TIFirm subscription does not requires any verification)

## Getting Started

To get started with the WhiteIntel API, you will need to obtain an API key. Detailed instructions for obtaining and using your API key can be found in our [Wiki](https://github.com/WhiteIntel/WhiteIntelAPI/wiki/).

## Documentation

Comprehensive documentation for all available endpoints and usage instructions are available in our [Wiki](https://github.com/WhiteIntel/WhiteIntelAPI/wiki/). Here are some quick links to key sections:

- [Authentication API](https://github.com/WhiteIntel/WhiteIntelAPI/wiki/Authentication)
- [Overall Stats API](https://github.com/WhiteIntel/WhiteIntelAPI/wiki/Overall-Stats-API)
- [Customer Leaks API](https://github.com/WhiteIntel/WhiteIntelAPI/wiki/Customer-Leaks-API)
- [Corporate Email Leaks API](https://github.com/WhiteIntel/WhiteIntelAPI/wiki/Corporate-Email-Leaks-API)

## Example Usage

Below is an example of how to make a POST request to the WhiteIntel API using `curl`:

```sh
curl -X POST https://api.whiteintel.io/api/endpoint \
     -H "Content-Type: application/json" \
     -d '{
           "apikey": "your_api_key_here",
           "other_parameter": "value"
         }'
```

For more detailed examples and usage scenarios, please refer to the [Wiki](https://github.com/WhiteIntel/WhiteIntelAPI/wiki/).

## Support

If you encounter any issues or have any questions, please refer to our Wiki or contact our support team at info@whiteintel.io.
