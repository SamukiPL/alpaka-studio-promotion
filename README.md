# Simple Promotion Repository

> For now promotion json and other files has to be done manually, until we gonna have buildSrc fully configured.

In this repository we have simple files that will be downloaded by our server and will be hosted by nginx. Our requirements are so small that there is no reason to develop API for soundboards(maybe some other apps in future).

## Security
### Never use this repository for important or sensitive data!
We doesn't have any authentication on our server, everything that will be uploaded on **master** will be public on **https://alpaka-studio.duckdns.org**
Maybe in the future some form o API will be created for security reasons.

## Server Updates
Server pulls master **every day on 2 AM**.

Other branches are safe from publicity.
