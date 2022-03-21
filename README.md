# FeedNext-2Vulns
## I Found 2 Critical Vulnerabilities On FeedNext Open Source...
-------------------------------------------------------------------------
### The First one is CVE-2017-18381:
#### Description:
- The installation process in Open edX before 2017-01-10 exposes a MongoDB instance to external connections with default credentials.
- The vulnerable section in the picture below - it's because MongoDB old version
- Severity = Critical
[Image of mahmoudashraf1344](https://github.com/0x1mahmoud/FeedNext-2Vulns/blob/main/images/MonoDB.png)
-----------------------------------------------------------------------------------------
### The Second One is CVE-2020-28168:
#### Description:
- Axios NPM package 0.21.0 contains a Server-Side Request Forgery (SSRF) vulnerability where an attacker is able to bypass a proxy by providing a URL that responds with a redirect to a restricted host or IP address.
- The vulnerable section in the picture below - it's because axios old version should be patched in version "0.21.1"
- Server-Side Request Forgery in Axios Found in
- Severity = High
[Image of mahmoudashraf1344](https://github.com/0x1mahmoud/FeedNext-2Vulns/blob/main/images/axios.png)
