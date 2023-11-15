# Voxscript Demos

Welcome to the Voxscript Demos repository! This resource is designed to demonstrate the use of the Voxscript REST API in various programming languages and scenarios.

## Getting Started

### Register for an API Key

To begin using the Voxscript REST API, you need to register for an API key. You can do this by visiting the following link:

[Register for API Key](https://voxscript-api.awt.icu/)

If you have previously filled out our early access survey, please use the same email for registration.

### API Definitions

You can find the definitions for the Voxscript API at the links below:

- [Voxscript API Definitions](https://voxscript.awt.icu/swagger/index.html)
- [OpenAPI JSON](https://voxscript.awt.icu/swagger/v1/swagger.json)
- [OpenAPI YAML](https://voxscript.awt.icu/swagger/v1/swagger.yaml)

**Note:** Currently, you need to add a server block to either the JSON or YAML files. Please refer to the example code for more details.

### Including Your API Token

Your API token can be included in your requests in one of three ways:

1. Bearer Token: `Bearer [token-here]`
2. API Key: `apiKey [token-here]`
3. URL Parameter: `https://voxscript.awt.icu/apikey/[token-here]/Help/ContactUs/`

### Example Usage

Below is an example of how to use the API with `curl`:

```bash
curl -X 'GET' \
  'https://voxscript.awt.icu/GetWebsiteContent?websiteURL=google.com&getLinks=false' \
  -H 'accept: */*' \
  -H 'Authorization: Bearer your-token-here'
  
## Contact Us

## Contact Us

We're always looking to connect with our users. Join us and become part of our community!

- **Discord:** Join us on [Discord](https://discord.gg/FZDWbJdQw2) for live discussions and support.
- **Subreddit:** Visit our [Subreddit](https://www.reddit.com/r/voxscript/) to engage with the community, share ideas, and get updates.
- **E-Mail** voxscript [at] allwiretech.com
