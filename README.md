# TinyURL

## Why do we need URL shortening?

URL shortening is used to create shorting aliases for long URLs. Users are redirected to the original URL when they hit
short URLs.

## Functional requirements
1. Given a URL, our service should generate a shorter and unique alias of it. THis is called a short links.
2. When users click these short links, our service should redirect to the original URL.
3. User should be able to custom url for their original URL.
4. Links should expire after a standard default timespan. user should be able to specify the expiration time.

##  Non-Functional requirements
1. The system should be highly available.
2. URL redirection should be happen real time with minimal latency.
3. Shortened links should not be guessable.