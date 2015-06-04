Meridium.ShareCountService
---

A service for retrieving and concatenation of share counts for various social media endpoints.

## Usage 

Instancing the service:

`var shareCountService = new ShareCountService();`

Add URLs to get count for:

`var keys = new List<string>() {"http://www.meridium.se", "http://www.github.com"};`

Retrieve Shares:

`var shares = shareCountService.GetShares(keys);`

## Currently supporting
- Facebook Open Graph
- Twitter API


## Dependencies
- [JSON.net](https://www.nuget.org/packages/Newtonsoft.Json/5.0.8)
- [NUnit](https://www.nuget.org/packages/NUnit/)
