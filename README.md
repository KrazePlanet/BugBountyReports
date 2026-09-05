# BugBountyReports

## Create Files
```console
curl -s "https://raw.githubusercontent.com/KrazePlanet/BugBountyReports/refs/heads/main/README.md" | grep -oP '\[View\]\(\K[^)]+' | xargs -n1 touch
```

## 📊 Progress

### Content Discovery

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 1 | [Redirect-Based Content Discovery](https://kzlabs.in/subdomains/japan) | 🟢 Easy | 🎓 Training | Not Solved | [View](redirect-based-content-discovery.md) |
| 2 | [404 Response-Based Discovery](https://kzlabs.in/subdomains/research) | 🟢 Easy | 🎓 Training | Not Solved | [View](404-response-based-discovery.md) |

### Hidden Parameter Fuzzing

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 3 | [Uncovering Hidden Parameters](https://kzlabs.in/subdomains/hide) | 🟢 Easy | 🎓 Training | Not Solved | [View](uncovering-hidden-parameters.md) |
| 4 | [Client-Side Parameter Discovery](https://kzlabs.in/subdomains/bbp) | 🟢 Easy | 🎓 Training | Not Solved | [View](client-side-parameter-discovery.md) |

### Cross-Site Scripting

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 5 | [Reflected XSS - TutorialRepublic: Web Development Reference Search](https://kzlabs.in/subdomains/tutorialrepublic) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-tutorialrepublic-web-development-reference-search.md) |
| 6 | [Reflected XSS - GIGW: Government Website Guidelines Portal](https://kzlabs.in/subdomains/guidelines) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-gigw-government-website-guidelines-portal.md) |
| 7 | [Reflected XSS - RefSeek: Academic & Scientific Search Engine](https://kzlabs.in/subdomains/refseek) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-refseek-academic-and-scientific-search-engine.md) |
| 8 | [Reflected XSS - PubMed: National Library of Medicine Search Builder](https://kzlabs.in/subdomains/pubmed) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-pubmed-national-library-of-medicine-search-builder.md) |
| 9 | [Reflected XSS - BigBasket: Online Supermarket Catalog](https://kzlabs.in/subdomains/bigbasket) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-bigbasket-online-supermarket-catalog.md) |
| 10 | [Reflected XSS - Global Site Search Portal](https://kzlabs.in/subdomains/search) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-global-site-search-portal.md) |
| 11 | [Reflected XSS - Script Tag Filter Evasion](https://kzlabs.in/subdomains/feedback) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-script-tag-filter-evasion.md) |
| 12 | [Reflected XSS - Multi-Parameter Script Filter Evasion](https://kzlabs.in/subdomains/cookbook) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-multi-parameter-script-filter-evasion.md) |
| 13 | [Reflected XSS - Path Based](https://kzlabs.in/subdomains/path-fetch) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-path-based.md) |
| 14 | [Reflected XSS - Script & Img Tag Filter](https://kzlabs.in/subdomains/support) | 🟡 Medium | 🎓 Training | Not Solved | [View](reflected-xss-script-and-img-tag-filter.md) |
| 15 | [Reflected XSS - Case-Insensitive Filter Bypass](https://kzlabs.in/subdomains/directory) | 🟡 Medium | 🎓 Training | Not Solved | [View](reflected-xss-case-insensitive-filter-bypass.md) |
| 16 | [Reflected XSS - HTML Tag Filter Bypass](https://kzlabs.in/subdomains/news) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-html-tag-filter-bypass.md) |
| 17 | [Reflected XSS - Page Heading](https://kzlabs.in/subdomains/docs) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-page-heading.md) |
| 18 | [Reflected XSS - Function Name Filter](https://kzlabs.in/subdomains/profile) | 🟢 Easy | 🎓 Training | Not Solved | [View](reflected-xss-function-name-filter.md) |
| 19 | [Reflected XSS - Extended Function Filter](https://kzlabs.in/subdomains/account) | 🟡 Medium | 🎓 Training | Not Solved | [View](reflected-xss-extended-function-filter.md) |
| 20 | [Reflected XSS - Event Handler Filter](https://kzlabs.in/subdomains/tickets) | 🟡 Medium | 🎓 Training | Not Solved | [View](reflected-xss-event-handler-filter.md) |
| 21 | [Reflected XSS - Multi-Parameter Filter Evasion](https://kzlabs.in/subdomains/checkout) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-multi-parameter-filter-evasion.md) |
| 22 | [Reflected XSS - Encoding Bypass Attempts](https://kzlabs.in/subdomains/mail) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-encoding-bypass-attempts.md) |
| 23 | [Reflected XSS - Mixed Security Parameters](https://kzlabs.in/subdomains/settings) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-mixed-security-parameters.md) |
| 24 | [Reflected XSS - String Concatenation Bypass](https://kzlabs.in/subdomains/portal) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-string-concatenation-bypass.md) |
| 25 | [DOM XSS in document.write sink using source location.search](https://kzlabs.in/subdomains/useruploads) | 🟢 Easy | 📚 DOM XSS | Not Solved | [View](dom-xss-in-document-write-sink-using-source-location-search.md) |
| 26 | [Reflected XSS - URL Encoding Context](https://kzlabs.in/subdomains/dashboard) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-url-encoding-context.md) |
| 27 | [Reflected XSS - Search Filter Bypass](https://kzlabs.in/subdomains/kb) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-search-filter-bypass.md) |
| 28 | [Reflected XSS - Category Filter](https://kzlabs.in/subdomains/shop) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-category-filter.md) |
| 29 | [Reflected XSS - Equifax](https://kzlabs.in/subdomains/tracking) | 🔴 Hard | 🌐 Real World | Not Solved | [View](reflected-xss-equifax.md) |
| 30 | [Reflected XSS - PUBG](https://kzlabs.in/subdomains/assets) | 🟢 Low | 🌐 Real World | Not Solved | [View](reflected-xss-pubg.md) |
| 31 | [Reflected XSS - Shopify](https://kzlabs.in/subdomains/go) | 🟢 Low | 🌐 Real World | Not Solved | [View](reflected-xss-shopify.md) |
| 32 | [Reflected XSS - Imgur Mobile](https://kzlabs.in/subdomains/media) | 🟡 Medium | 🌐 Real World | Not Solved | [View](reflected-xss-imgur-mobile.md) |
| 33 | [Reflected XSS - Reddit](https://kzlabs.in/subdomains/widgets) | 🔴 Hard | 🌐 Real World | Not Solved | [View](reflected-xss-reddit.md) |
| 34 | [Stored XSS - Forum Discussions (Reddit Clone)](https://kzlabs.in/subdomains/community) | 🔴 Hard | 🎓 Training | Not Solved | [View](stored-xss-forum-discussions-reddit-clone.md) |
| 35 | [Stored XSS - Product Reviews (Flipkart Clone)](https://kzlabs.in/subdomains/members) | 🔴 Hard | 🎓 Training | Not Solved | [View](stored-xss-product-reviews-flipkart-clone.md) |
| 36 | [Stored XSS - Events & Polls Activity Center](https://kzlabs.in/subdomains/articles) | 🔴 Hard | 🎓 Training | Not Solved | [View](stored-xss-events-and-polls-activity-center.md) |
| 37 | [Stored XSS - Support Center (DigitalOcean Clone)](https://kzlabs.in/subdomains/digitalocean) | 🔴 Hard | 🎓 Training | Not Solved | [View](stored-xss-support-center-digitalocean-clone.md) |
| 38 | [Stored XSS - Bug Bounty Platform (HackerOne Clone)](https://kzlabs.in/subdomains/hackerone) | 🔴 Hard | 🎓 Training | Not Solved | [View](stored-xss-bug-bounty-platform-hackerone-clone.md) |
| 39 | [Stored XSS - Video Streaming Service (Netflix Clone)](https://kzlabs.in/subdomains/netflix) | 🔴 Hard | 🎓 Training | Not Solved | [View](stored-xss-video-streaming-service-netflix-clone.md) |
| 40 | [CSP Bypass - Unsafe Inline Scripts](https://kzlabs.in/subdomains/48.php) | 🔴 Hard | 🎓 Training | Not Solved | [View](csp-bypass-unsafe-inline-scripts.md) |
| 41 | [CSP Protected Page](https://kzlabs.in/subdomains/49.php) | 🔴 Hard | 🎓 Training | Not Solved | [View](csp-protected-page.md) |
| 42 | [Stored XSS - Twitter](https://kzlabs.in/subdomains/ads) | 🔴 Hard | 🌐 Real World | Not Solved | [View](stored-xss-twitter.md) |
| 43 | [Stored XSS - Shopify](https://kzlabs.in/subdomains/cms) | 🟡 Medium | 🌐 Real World | Not Solved | [View](stored-xss-shopify.md) |
| 44 | [Stored XSS - Acronis](https://kzlabs.in/subdomains/forum) | 🟡 Medium | 🌐 Real World | Not Solved | [View](stored-xss-acronis.md) |
| 45 | [Blind XSS - ZAP-Hosting](https://kzlabs.in/subdomains/contact) | 🔴 Hard | 🌐 Real World | Not Solved | [View](blind-xss-zap-hosting.md) |
| 46 | [Blind Stored XSS - Informatica](https://kzlabs.in/subdomains/partners) | 🟡 Medium | 🌐 Real World | Not Solved | [View](blind-stored-xss-informatica.md) |
| 47 | [DOM XSS - IMDb: Ratings, Reviews, and Where to Watch the Best Movies & TV Shows](https://kzlabs.in/subdomains/imdb) | 🔴 Hard | 🎓 Training | Not Solved | [View](dom-xss-imdb-ratings-reviews-and-where-to-watch-the-best-movies-and-tv-shows.md) |
| 48 | [DOM XSS - AniList: Explore, Track, and Discover Anime & Manga](https://kzlabs.in/subdomains/anilist) | 🔴 Hard | 🎓 Training | Not Solved | [View](dom-xss-anilist-explore-track-and-discover-anime-and-manga.md) |
| 49 | [DOM XSS - MilesWeb: Fast, Secure & Reliable Web Hosting Built for Indian Websites](https://kzlabs.in/subdomains/milesweb) | 🔴 Hard | 🎓 Training | Not Solved | [View](dom-xss-milesweb-fast-secure-and-reliable-web-hosting-built-for-indian-websites.md) |
| 50 | [DOM XSS - Censys Search - Internet Intelligence Platform](https://kzlabs.in/subdomains/censys) | 🔴 Hard | 🎓 Training | Not Solved | [View](dom-xss-censys-search-internet-intelligence-platform.md) |
| 51 | [DOM XSS - HackerOne](https://kzlabs.in/subdomains/careers) | 🟡 Medium | 🌐 Real World | Not Solved | [View](dom-xss-hackerone.md) |
| 52 | [DOM XSS - MyCrypto](https://kzlabs.in/subdomains/wallet) | 🟡 Medium | 🌐 Real World | Not Solved | [View](dom-xss-mycrypto.md) |
| 53 | [DOM XSS - Starbucks](https://kzlabs.in/subdomains/cafe) | 🔴 Hard | 🌐 Real World | Not Solved | [View](dom-xss-starbucks.md) |
| 54 | [DOM XSS - ForeScout Technologies](https://kzlabs.in/subdomains/gallery) | 🟡 Medium | 🌐 Real World | Not Solved | [View](dom-xss-forescout-technologies.md) |
| 55 | [DOM XSS - Informatica](https://kzlabs.in/subdomains/auth) | 🟡 Medium | 🌐 Real World | Not Solved | [View](dom-xss-informatica.md) |
| 56 | [Self XSS - via POST Parameter](https://kzlabs.in/subdomains/forms) | 🔴 Hard | 🎓 Training | Not Solved | [View](self-xss-via-post-parameter.md) |
| 57 | [Self XSS - POST-Based Reflected XSS](https://kzlabs.in/subdomains/apply) | 🔴 Hard | 🎓 Training | Not Solved | [View](self-xss-post-based-reflected-xss.md) |
| 58 | [Self XSS - POST XSS in Input Tag Value](https://kzlabs.in/subdomains/survey) | 🔴 Hard | 🎓 Training | Not Solved | [View](self-xss-post-xss-in-input-tag-value.md) |
| 59 | [Self XSS - in Document Title](https://kzlabs.in/subdomains/reports) | 🔴 Hard | 🎓 Training | Not Solved | [View](self-xss-in-document-title.md) |
| 60 | [Reflected XSS - Cloud Instance Console](https://kzlabs.in/subdomains/instance) | 🔵 Secure | 🎓 Training | Not Solved | [View](reflected-xss-cloud-instance-console.md) |
| 61 | [Reflected XSS - HTML Tag Blacklist Filter](https://kzlabs.in/subdomains/board) | 🔵 Secure | 🎓 Training | Not Solved | [View](reflected-xss-html-tag-blacklist-filter.md) |
| 62 | [Reflected XSS to Account Takeover](https://kzlabs.in/subdomains/pixeleet) | 🔴 Hard | 🎓 Training | Not Solved | [View](reflected-xss-to-account-takeover.md) |
| 63 | [PUNISHMENT LAB 1](https://kzlabs.in/subdomains/webmail) | 🟢 Easy | 🎓 Training | Not Solved | [View](punishment-lab-1.md) |
| 64 | [PUNISHMENT LAB 2](https://kzlabs.in/subdomains/cpanel) | 🟢 Easy | 🎓 Training | Not Solved | [View](punishment-lab-2.md) |
| 65 | [PUNISHMENT LAB 3](https://kzlabs.in/subdomains/webdisk) | 🟡 Medium | 🎓 Training | Not Solved | [View](punishment-lab-3.md) |
| 66 | [PUNISHMENT LAB 4](https://kzlabs.in/subdomains/cpcontacts) | 🟡 Medium | 🎓 Training | Not Solved | [View](punishment-lab-4.md) |
| 67 | [PUNISHMENT LAB 5](https://kzlabs.in/subdomains/cpcalendars) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-5.md) |
| 68 | [PUNISHMENT LAB 6](https://kzlabs.in/subdomains/autodiscover) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-6.md) |
| 69 | [PUNISHMENT LAB 7](https://kzlabs.in/subdomains/wildcard) | 🟢 Easy | 🎓 Training | Not Solved | [View](punishment-lab-7.md) |
| 70 | [PUNISHMENT LAB 8](https://kzlabs.in/subdomains/hostmaster) | 🟢 Easy | 🎓 Training | Not Solved | [View](punishment-lab-8.md) |
| 71 | [PUNISHMENT LAB 9](https://kzlabs.in/subdomains/protection) | 🟡 Medium | 🎓 Training | Not Solved | [View](punishment-lab-9.md) |
| 72 | [PUNISHMENT LAB 10](https://kzlabs.in/subdomains/cloudapp) | 🟡 Medium | 🎓 Training | Not Solved | [View](punishment-lab-10.md) |
| 73 | [PUNISHMENT LAB 11](https://kzlabs.in/subdomains/pay) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-11.md) |
| 74 | [PUNISHMENT LAB 12](https://kzlabs.in/subdomains/atlas) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-12.md) |
| 75 | [PUNISHMENT LAB 13](https://kzlabs.in/subdomains/avito) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-13.md) |
| 76 | [PUNISHMENT LAB 14](https://kzlabs.in/subdomains/app) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-14.md) |
| 77 | [PUNISHMENT LAB 15](https://kzlabs.in/subdomains/admin) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-15.md) |
| 78 | [PUNISHMENT LAB 16](https://kzlabs.in/subdomains/dev) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-16.md) |
| 79 | [PUNISHMENT LAB 17](https://kzlabs.in/subdomains/staging) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-17.md) |
| 80 | [PUNISHMENT LAB 18](https://kzlabs.in/subdomains/sberbank) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-18.md) |
| 81 | [PUNISHMENT LAB 19](https://kzlabs.in/subdomains/demo) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-19.md) |
| 82 | [PUNISHMENT LAB 20](https://kzlabs.in/subdomains/test) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-20.md) |
| 83 | [PUNISHMENT LAB 21](https://kzlabs.in/subdomains/nalozhka) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-21.md) |
| 84 | [PUNISHMENT LAB 22](https://kzlabs.in/subdomains/sitemap) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-22.md) |
| 85 | [PUNISHMENT LAB 23](https://kzlabs.in/subdomains/sbermarket) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-23.md) |
| 86 | [PUNISHMENT LAB 24](https://kzlabs.in/subdomains/pochtabank) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-24.md) |
| 87 | [PUNISHMENT LAB 25](https://kzlabs.in/subdomains/remote) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-25.md) |
| 88 | [PUNISHMENT LAB 26](https://kzlabs.in/subdomains/store) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-26.md) |
| 89 | [PUNISHMENT LAB 27](https://kzlabs.in/subdomains/smtp) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-27.md) |
| 90 | [PUNISHMENT LAB 28](https://kzlabs.in/subdomains/cdn) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-28.md) |
| 91 | [PUNISHMENT LAB 29](https://kzlabs.in/subdomains/pop) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-29.md) |
| 92 | [PUNISHMENT LAB 30](https://kzlabs.in/subdomains/secure) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-30.md) |
| 93 | [PUNISHMENT LAB 31](https://kzlabs.in/subdomains/apps) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-31.md) |
| 94 | [PUNISHMENT LAB 32](https://kzlabs.in/subdomains/cust) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-32.md) |
| 95 | [PUNISHMENT LAB 33](https://kzlabs.in/subdomains/old) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-33.md) |
| 96 | [PUNISHMENT LAB 34](https://kzlabs.in/subdomains/uaecentral) | 🔴 Hard | 🎓 Training | Not Solved | [View](punishment-lab-34.md) |

### HTML Injection

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 97 | [HTML Injection - E-commerce](https://kzlabs.in/subdomains/catalog) | 🟢 Easy | 🎓 Training | Not Solved | [View](html-injection-e-commerce.md) |
| 98 | [HTML Injection - LinkedIn](https://kzlabs.in/subdomains/chat) | 🟢 Easy | 🌐 Real World | Not Solved | [View](html-injection-linkedin.md) |
| 99 | [Stored HTML Injection - Romit](https://kzlabs.in/subdomains/transfer) | 🟢 Easy | 🌐 Real World | Not Solved | [View](stored-html-injection-romit.md) |
| 100 | [Stored HTML Tag Injection - GitLab](https://kzlabs.in/subdomains/code) | 🟢 Easy | 🌐 Real World | Not Solved | [View](stored-html-tag-injection-gitlab.md) |
| 101 | [HTML Injection - HackerOne](https://kzlabs.in/subdomains/notifications) | 🟡 Medium | 🌐 Real World | Not Solved | [View](html-injection-hackerone.md) |

### Open Redirect

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 102 | [Basic URL Parameter Redirect](https://kzlabs.in/subdomains/redirect) | 🟢 Easy | 🎓 Training | Not Solved | [View](basic-url-parameter-redirect.md) |
| 103 | [Open Redirect - Omise](https://kzlabs.in/subdomains/links) | 🟢 Easy | 🌐 Real World | Not Solved | [View](open-redirect-omise.md) |
| 104 | [Open Redirect - Semrush](https://kzlabs.in/subdomains/out) | 🟢 Easy | 🌐 Real World | Not Solved | [View](open-redirect-semrush.md) |
| 105 | [Open Redirect - Tumblr](https://kzlabs.in/subdomains/sso) | 🟡 Medium | 🌐 Real World | Not Solved | [View](open-redirect-tumblr.md) |

### Authentication Bypass

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 106 | [Admin Auth Bypass - UPS](https://kzlabs.in/subdomains/adminpanel) | 🟡 Medium | 🌐 Real World | Not Solved | [View](admin-auth-bypass-ups.md) |
| 107 | [OTP Verification Bypass via Response Manipulation](https://kzlabs.in/subdomains/verify) | 🟡 Medium | 🎓 Training | Not Solved | [View](otp-verification-bypass-via-response-manipulation.md) |
| 108 | [Phone OTP Bypass via Response Manipulation](https://kzlabs.in/subdomains/mobile) | 🟡 Medium | 🎓 Training | Not Solved | [View](phone-otp-bypass-via-response-manipulation.md) |

### No Rate Limiting

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 109 | [No Rate Limiting](https://kzlabs.in/subdomains/codeshackio) | 🟢 Easy | 🎓 Training | Not Solved | [View](no-rate-limiting.md) |
| 110 | [Yelp for Business - Missing Rate Limiting on Subscription Form](https://kzlabs.in/subdomains/rl-testing) | 🔴 Hard | 🌐 Real World | Not Solved | [View](yelp-for-business-missing-rate-limiting-on-subscription-form.md) |
| 111 | [On Running - Missing Rate Limiting on Partner Authentication Endpoint](https://kzlabs.in/subdomains/security-test) | 🔴 Hard | 🌐 Real World | Not Solved | [View](on-running-missing-rate-limiting-on-partner-authentication-endpoint.md) |
| 112 | [Courier - Missing Rate Limiting on User Registration & Email Enumeration](https://kzlabs.in/subdomains/stress) | 🔴 Hard | 🌐 Real World | Not Solved | [View](courier-missing-rate-limiting-on-user-registration-and-email-enumeration.md) |
| 113 | [WakaTime - Rate Limit Too Lenient on Password Reset Endpoint](https://kzlabs.in/subdomains/request) | 🔴 Hard | 🌐 Real World | Not Solved | [View](wakatime-rate-limit-too-lenient-on-password-reset-endpoint.md) |
| 114 | [Redditgifts - Missing Rate Limiting on Adding Comments](https://kzlabs.in/subdomains/load) | 🔴 Hard | 🌐 Real World | Not Solved | [View](redditgifts-missing-rate-limiting-on-adding-comments.md) |
| 115 | [Nextcloud - Missing Rate Limiting on Newsletter Subscription Endpoint](https://kzlabs.in/subdomains/throttle) | 🔴 Hard | 🌐 Real World | Not Solved | [View](nextcloud-missing-rate-limiting-on-newsletter-subscription-endpoint.md) |
| 116 | [UPchieve - Missing Rate Limiting on Contact Us Endpoint](https://kzlabs.in/subdomains/limit) | 🔴 Hard | 🌐 Real World | Not Solved | [View](upchieve-missing-rate-limiting-on-contact-us-endpoint.md) |
| 117 | [Algolia - Missing Rate Limiting on Two-Factor Authentication (2FA) Code Verification](https://kzlabs.in/subdomains/rate) | 🔴 Hard | 🌐 Real World | Not Solved | [View](algolia-missing-rate-limiting-on-two-factor-authentication-2fa-code-verification.md) |
| 118 | [UPchieve - Missing Rate Limiting on Password Reset Endpoint](https://kzlabs.in/subdomains/ratelimit) | 🔴 Hard | 🌐 Real World | Not Solved | [View](upchieve-missing-rate-limiting-on-password-reset-endpoint.md) |
| 119 | [Yelp for Business - Missing Rate Limiting on Resend Confirmation Email Endpoint](https://kzlabs.in/subdomains/reset) | 🔴 Hard | 🌐 Real World | Not Solved | [View](yelp-for-business-missing-rate-limiting-on-resend-confirmation-email-endpoint.md) |
| 120 | [MTN Group - Missing Rate Limiting on 5-Digit OTP Verification Endpoint](https://kzlabs.in/subdomains/resend) | 🔴 Hard | 🌐 Real World | Not Solved | [View](mtn-group-missing-rate-limiting-on-5-digit-otp-verification-endpoint.md) |

### Race Condition

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 121 | [CodeShack - Race Condition in OTP Resend Limit Bypass](https://kzlabs.in/subdomains/counter) | 🟢 Easy | 🎓 Training | Not Solved | [View](codeshack-race-condition-in-otp-resend-limit-bypass.md) |
| 122 | [Slack - Race Condition in Account Creation Survey (Unlimited Credits)](https://kzlabs.in/subdomains/race_condition) | 🔴 Hard | 🌐 Real World | Not Solved | [View](slack-race-condition-in-account-creation-survey-unlimited-credits.md) |
| 123 | [Omise - Race Condition in Team Member Invitations](https://kzlabs.in/subdomains/condition) | 🔴 Hard | 🌐 Real World | Not Solved | [View](omise-race-condition-in-team-member-invitations.md) |
| 124 | [HackerOne - Race Condition in Claiming Program Credentials](https://kzlabs.in/subdomains/flashdisk) | 🔴 Hard | 🌐 Real World | Not Solved | [View](hackerone-race-condition-in-claiming-program-credentials.md) |
| 125 | [Hacker101 CTF - Race Condition in Flag Submission](https://kzlabs.in/subdomains/dropper) | 🔴 Hard | 🌐 Real World | Not Solved | [View](hacker101-ctf-race-condition-in-flag-submission.md) |
| 126 | [Urban Dictionary - Race Condition in Definition Votes](https://kzlabs.in/subdomains/cablej) | 🔴 Hard | 🌐 Real World | Not Solved | [View](urban-dictionary-race-condition-in-definition-votes.md) |
| 127 | [Dust - Race Condition in Folder Creation (Folder Limit Bypass)](https://kzlabs.in/subdomains/duststaff) | 🔴 Hard | 🌐 Real World | Not Solved | [View](dust-race-condition-in-folder-creation-folder-limit-bypass.md) |

### OAuth Misconfiguration

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 128 | [OAuth Misconfiguration](https://kzlabs.in/subdomains/misconfiguration) | 🟢 Easy | 🎓 Training | Not Solved | [View](oauth-misconfiguration.md) |

### Information Disclosure

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 129 | [The Forgotten Release](https://kzlabs.in/subdomains/bird) | 🟢 Easy | 🎓 Training | Not Solved | [View](the-forgotten-release.md) |
| 130 | [Open to the World](https://kzlabs.in/subdomains/pc) | 🟢 Easy | 🎓 Training | Not Solved | [View](open-to-the-world.md) |
| 131 | [The Unseen Layer](https://kzlabs.in/subdomains/analytics) | 🟢 Easy | 🎓 Training | Not Solved | [View](the-unseen-layer.md) |
| 132 | [Under the Hood](https://kzlabs.in/subdomains/campuscloud) | 🟢 Easy | 🎓 Training | Not Solved | [View](under-the-hood.md) |
| 133 | [The Research Vault](https://kzlabs.in/subdomains/researcher) | 🟢 Easy | 🎓 Training | Not Solved | [View](the-research-vault.md) |
| 134 | [Behind the Profile](https://kzlabs.in/subdomains/profiler) | 🟢 Easy | 🎓 Training | Not Solved | [View](behind-the-profile.md) |
| 135 | [CDN Directory Listing - PII Exposed](https://kzlabs.in/subdomains/edge) | 🔴 Hard | 🎓 Training | Not Solved | [View](cdn-directory-listing-pii-exposed.md) |

### Username/Email Enumeration

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 136 | [UPchieve - User & Email Enumeration via Password Reset](https://kzlabs.in/subdomains/username_enum) | 🟢 Easy | 🎓 Training | Not Solved | [View](upchieve-user-and-email-enumeration-via-password-reset.md) |

### Using Default Credentials

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 137 | [Default Credentials](https://kzlabs.in/subdomains/defaultlogin) | 🟢 Easy | 🎓 Training | Not Solved | [View](default-credentials.md) |

### SQL Injection

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 138 | [SQL Injection - GET Parameter](https://kzlabs.in/subdomains/courses) | 🟢 Easy | 🎓 Training | Not Solved | [View](sql-injection-get-parameter.md) |
| 139 | [SQL Injection - Login Bypass](https://kzlabs.in/subdomains/login) | 🟢 Easy | 🎓 Training | Not Solved | [View](sql-injection-login-bypass.md) |
| 140 | [INSERT SQL Injection - Comment System](https://kzlabs.in/subdomains/reviews) | 🟢 Easy | 🎓 Training | Not Solved | [View](insert-sql-injection-comment-system.md) |
| 141 | [CRUD SQL Injection - Book Management](https://kzlabs.in/subdomains/library) | 🟡 Medium | 🎓 Training | Not Solved | [View](crud-sql-injection-book-management.md) |
| 142 | [Time-based Blind SQL Injection](https://kzlabs.in/subdomains/inventory) | 🟡 Medium | 🎓 Training | Not Solved | [View](time-based-blind-sql-injection.md) |
| 143 | [Integer-based SQL Injection](https://kzlabs.in/subdomains/orders) | 🟡 Medium | 🎓 Training | Not Solved | [View](integer-based-sql-injection.md) |
| 144 | [User-Agent Header Blind SQL Injection](https://kzlabs.in/subdomains/stats) | 🔴 Hard | 🎓 Training | Not Solved | [View](user-agent-header-blind-sql-injection.md) |
| 145 | [Referer Header Blind SQL Injection](https://kzlabs.in/subdomains/affiliate) | 🔴 Hard | 🎓 Training | Not Solved | [View](referer-header-blind-sql-injection.md) |
| 146 | [X-Forwarded-For Header Blind SQL Injection](https://kzlabs.in/subdomains/proxy) | 🔴 Hard | 🎓 Training | Not Solved | [View](x-forwarded-for-header-blind-sql-injection.md) |
| 147 | [Blind SQL Injection via Parameter name - Executive Dashboard](https://kzlabs.in/subdomains/executive) | 🔴 Hard | 🎓 Training | Not Solved | [View](blind-sql-injection-via-parameter-name-executive-dashboard.md) |
| 148 | [Blind SQL Injection via PATH_INFO - Industrial Asset Registry](https://kzlabs.in/subdomains/registry) | 🔴 Hard | 🎓 Training | Not Solved | [View](blind-sql-injection-via-path-info-industrial-asset-registry.md) |
| 149 | [Blind SQL Injection via Filename - University Course Catalog](https://kzlabs.in/subdomains/academic) | 🔴 Hard | 🎓 Training | Not Solved | [View](blind-sql-injection-via-filename-university-course-catalog.md) |
| 150 | [Time-based Blind SQLi via sitemap.xml - ACME Corp Industrial](https://kzlabs.in/subdomains/industrial) | 🔴 Hard | 🎓 Training | Not Solved | [View](time-based-blind-sqli-via-sitemap-xml-acme-corp-industrial.md) |
| 151 | [Time-based Blind SQLi - Zomato](https://kzlabs.in/subdomains/menu) | 🔴 Hard | 🌐 Real World | Not Solved | [View](time-based-blind-sqli-zomato.md) |
| 152 | [Time-based Blind SQLi - GSA Bounty](https://kzlabs.in/subdomains/collector) | 🔴 Hard | 🌐 Real World | Not Solved | [View](time-based-blind-sqli-gsa-bounty.md) |
| 153 | [UNION-based SQLi - IntenseDebate](https://kzlabs.in/subdomains/directoryapi) | 🔴 Hard | 🌐 Real World | Not Solved | [View](union-based-sqli-intensedebate.md) |
| 154 | [Blind SQLi - MTN Group](https://kzlabs.in/subdomains/customers) | 🔴 Hard | 🌐 Real World | Not Solved | [View](blind-sqli-mtn-group.md) |
| 155 | [ORDER BY SQLi - Grab](https://kzlabs.in/subdomains/content) | 🔴 Hard | 🌐 Real World | Not Solved | [View](order-by-sqli-grab.md) |
| 156 | [Boolean-blind SQLi - inDrive](https://kzlabs.in/subdomains/api) | 🔴 Hard | 🌐 Real World | Not Solved | [View](boolean-blind-sqli-indrive.md) |
| 157 | [Time-Based Blind SQLi - Rocket.Chat](https://kzlabs.in/subdomains/events) | 🔴 Hard | 🌐 Real World | Not Solved | [View](time-based-blind-sqli-rocket-chat.md) |
| 158 | [Boolean-Blind SQLi - Zomato](https://kzlabs.in/subdomains/rest) | 🔴 Hard | 🌐 Real World | Not Solved | [View](boolean-blind-sqli-zomato.md) |
| 159 | [UNION-Based SQLi - Acronis](https://kzlabs.in/subdomains/adminapi) | 🔴 Hard | 🌐 Real World | Not Solved | [View](union-based-sqli-acronis.md) |
| 160 | [UNION SQLi - Automattic](https://kzlabs.in/subdomains/coupons) | 🔴 Hard | 🌐 Real World | Not Solved | [View](union-sqli-automattic.md) |
| 161 | [Time-Based Blind SQLi - Acronis](https://kzlabs.in/subdomains/memberships) | 🔴 Hard | 🌐 Real World | Not Solved | [View](time-based-blind-sqli-acronis.md) |
| 162 | [UNION SQLi - U.S. Dept Of Defense](https://kzlabs.in/subdomains/ajax) | 🔴 Hard | 🌐 Real World | Not Solved | [View](union-sqli-u-s-dept-of-defense.md) |
| 163 | [Blind SQLi - Zomato](https://kzlabs.in/subdomains/banners) | 🔴 Hard | 🌐 Real World | Not Solved | [View](blind-sqli-zomato.md) |
| 164 | [Time-Based Blind SQLi - Automattic](https://kzlabs.in/subdomains/moderation) | 🟡 Medium | 🌐 Real World | Not Solved | [View](time-based-blind-sqli-automattic.md) |
| 165 | [String SQLi - U.S. Dept Of Defense](https://kzlabs.in/subdomains/publications) | 🔴 Hard | 🌐 Real World | Not Solved | [View](string-sqli-u-s-dept-of-defense.md) |
| 166 | [Time-Based Blind SQLi - U.S. Dept Of Defense](https://kzlabs.in/subdomains/knowledge) | 🟡 Medium | 🌐 Real World | Not Solved | [View](time-based-blind-sqli-u-s-dept-of-defense.md) |

### Cross-Site Request Forgery

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 167 | [CSRF Password Change - Unprotected Account Settings](https://kzlabs.in/subdomains/security) | 🟢 Easy | 🎓 Training | Not Solved | [View](csrf-password-change-unprotected-account-settings.md) |
| 168 | [CSRF Email Hijack - Silent Account Takeover](https://kzlabs.in/subdomains/preferences) | 🟢 Easy | 🎓 Training | Not Solved | [View](csrf-email-hijack-silent-account-takeover.md) |
| 169 | [CSRF Account Wipe - Irreversible Data Deletion](https://kzlabs.in/subdomains/privacy) | 🟢 Easy | 🎓 Training | Not Solved | [View](csrf-account-wipe-irreversible-data-deletion.md) |
| 170 | [CSRF 2FA Bypass - Silent Security Downgrade](https://kzlabs.in/subdomains/mfa) | 🟢 Easy | 🎓 Training | Not Solved | [View](csrf-2fa-bypass-silent-security-downgrade.md) |
| 171 | [Login CSRF - HackerOne](https://kzlabs.in/subdomains/session) | 🟢 Easy | 🌐 Real World | Not Solved | [View](login-csrf-hackerone.md) |
| 172 | [Login CSRF - Unikrn](https://kzlabs.in/subdomains/identity) | 🟡 Medium | 🌐 Real World | Not Solved | [View](login-csrf-unikrn.md) |
| 173 | [CSRF - GitLab](https://kzlabs.in/subdomains/graphql) | 🔴 Hard | 🌐 Real World | Not Solved | [View](csrf-gitlab.md) |
| 174 | [CSRF - Starbucks](https://kzlabs.in/subdomains/wishlist) | 🟡 Medium | 🌐 Real World | Not Solved | [View](csrf-starbucks.md) |
| 175 | [CSRF - U.S. Dept of Defense](https://kzlabs.in/subdomains/myaccount) | 🔴 Hard | 🌐 Real World | Not Solved | [View](csrf-u-s-dept-of-defense.md) |
| 176 | [CSRF - U.S. Dept of Defense](https://kzlabs.in/subdomains/academy) | 🟡 Medium | 🌐 Real World | Not Solved | [View](csrf-u-s-dept-of-defense.md) |

### Insecure Direct Object Reference

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 177 | [SwiftCart - Insecure Order Invoice Disclosure](https://kzlabs.in/subdomains/billing) | 🟢 Easy | 🎓 Training | Not Solved | [View](swiftcart-insecure-order-invoice-disclosure.md) |
| 178 | [MediCare+ - Healthcare Records IDOR](https://kzlabs.in/subdomains/patient) | 🟢 Easy | 🎓 Training | Not Solved | [View](medicare-healthcare-records-idor.md) |
| 179 | [FriendZone - Social Media Profile IDOR](https://kzlabs.in/subdomains/social) | 🟡 Medium | 🎓 Training | Not Solved | [View](friendzone-social-media-profile-idor.md) |
| 180 | [SecureBank - Banking Portal Account IDOR](https://kzlabs.in/subdomains/bank) | 🟡 Medium | 🎓 Training | Not Solved | [View](securebank-banking-portal-account-idor.md) |
| 181 | [Uber Driver Portal - Trip & Earnings Disclosure](https://kzlabs.in/subdomains/driver) | 🟡 Medium | 🌐 Real World | Not Solved | [View](uber-driver-portal-trip-and-earnings-disclosure.md) |

### Privilege Escalation

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 182 | [Privilege Escalation](https://kzlabs.in/subdomains/escalation) | 🟢 Easy | 🎓 Training | Not Solved | [View](privilege-escalation.md) |

### Local File Inclusion

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 183 | [Path Traversal - Basic](https://kzlabs.in/subdomains/files) | 🟢 Easy | 🎓 Training | Not Solved | [View](path-traversal-basic.md) |
| 184 | [CMS Local File Inclusion](https://kzlabs.in/subdomains/storage) | 🟡 Medium | 🎓 Training | Not Solved | [View](cms-local-file-inclusion.md) |
| 185 | [File Upload with LFI Vulnerability](https://kzlabs.in/subdomains/uploads) | 🔴 Hard | 🎓 Training | Not Solved | [View](file-upload-with-lfi-vulnerability.md) |
| 186 | [Image Gallery File Inclusion](https://kzlabs.in/subdomains/archive) | 🟢 Easy | 🎓 Training | Not Solved | [View](image-gallery-file-inclusion.md) |
| 187 | [Local File Inclusion - Corporate Page Routing](https://kzlabs.in/subdomains/corporate) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-corporate-page-routing.md) |
| 188 | [Local File Inclusion - Documentation Portal Engine](https://kzlabs.in/subdomains/doc-portal) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-documentation-portal-engine.md) |
| 189 | [Local File Inclusion - Multi-Language Blog CMS](https://kzlabs.in/subdomains/multilang-blog) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-multi-language-blog-cms.md) |
| 190 | [Local File Inclusion - HR Portal File Preview](https://kzlabs.in/subdomains/hr-portal) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-hr-portal-file-preview.md) |
| 191 | [Local File Inclusion - Help Desk Attachment Preview](https://kzlabs.in/subdomains/helpdesk) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-help-desk-attachment-preview.md) |
| 192 | [Local File Inclusion - LMS Course Resource Viewer](https://kzlabs.in/subdomains/lms) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-lms-course-resource-viewer.md) |
| 193 | [Local File Inclusion - Hospital EMR Medical Report Viewer](https://kzlabs.in/subdomains/hospital) | 🔴 Hard | 🎓 Training | Not Solved | [View](local-file-inclusion-hospital-emr-medical-report-viewer.md) |
| 194 | [Local File Inclusion - Real Estate CMS Media Loader](https://kzlabs.in/subdomains/realestate) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-real-estate-cms-media-loader.md) |
| 195 | [Local File Inclusion - Hosting Panel Log Viewer](https://kzlabs.in/subdomains/hosting-panel) | 🔴 Hard | 🎓 Training | Not Solved | [View](local-file-inclusion-hosting-panel-log-viewer.md) |
| 196 | [Local File Inclusion - E-Commerce Invoice & Template Renderer](https://kzlabs.in/subdomains/ecommerce) | 🟡 Medium | 🎓 Training | Not Solved | [View](local-file-inclusion-e-commerce-invoice-and-template-renderer.md) |
| 197 | [RecipeBox - Base64-Encoded Path LFI Bypass](https://kzlabs.in/subdomains/recipes) | 🔴 Hard | 🎓 Training | Not Solved | [View](recipebox-base64-encoded-path-lfi-bypass.md) |
| 198 | [GovDocs - Double URL Encoding LFI Bypass](https://kzlabs.in/subdomains/gov) | 🔴 Hard | 🎓 Training | Not Solved | [View](govdocs-double-url-encoding-lfi-bypass.md) |
| 199 | [Admin Portal - Error Parameter Path Traversal](https://kzlabs.in/subdomains/control) | 🔴 Hard | 🎓 Training | Not Solved | [View](admin-portal-error-parameter-path-traversal.md) |

### Remote Code Execution

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 200 | [OS Command Injection](https://kzlabs.in/subdomains/diagnostics) | 🟢 Easy | 🎓 Training | Not Solved | [View](os-command-injection.md) |
| 201 | [RCE via File Upload](https://kzlabs.in/subdomains/pixeleet) | 🔴 Hard | 🎓 Training | Not Solved | [View](rce-via-file-upload.md) |

### Server-Side Template Injection

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 202 | [CloudGuard - Enterprise Compliance & Security Report Engine Code Execution](https://kzlabs.in/subdomains/jinja2) | 🔴 Hard | 🎓 Training | Not Solved | [View](cloudguard-enterprise-compliance-and-security-report-engine-code-execution.md) |
| 203 | [TornadoAlert - Python SRE Incident & Webhook Notification Code Execution](https://kzlabs.in/subdomains/tornado) | 🔴 Hard | 🎓 Training | Not Solved | [View](tornadoalert-python-sre-incident-and-webhook-notification-code-execution.md) |
| 204 | [DocuCraft - Cloud Invoice & Billing Template Engine Code Execution](https://kzlabs.in/subdomains/erb) | 🔴 Hard | 🎓 Training | Not Solved | [View](docucraft-cloud-invoice-and-billing-template-engine-code-execution.md) |
| 205 | [PulseMail - Marketing Campaign Template Studio Code Execution](https://kzlabs.in/subdomains/freemarker) | 🔴 Hard | 🎓 Training | Not Solved | [View](pulsemail-marketing-campaign-template-studio-code-execution.md) |
| 206 | [Template Engine Code Injection](https://kzlabs.in/subdomains/templates) | 🟢 Easy | 🎓 Training | Not Solved | [View](template-engine-code-injection.md) |
| 207 | [SSTI - Glovo](https://kzlabs.in/subdomains/onboarding) | 🟡 Medium | 🌐 Real World | Not Solved | [View](ssti-glovo.md) |
| 208 | [SSTI - Uber](https://kzlabs.in/subdomains/accounts) | 🟡 Medium | 🌐 Real World | Not Solved | [View](ssti-uber.md) |
| 209 | [SSTI - Unikrn](https://kzlabs.in/subdomains/invite) | 🔴 Hard | 🌐 Real World | Not Solved | [View](ssti-unikrn.md) |

### Server-Side Request Forgery

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 210 | [Source Code Viewer - Basic cURL SSRF](https://kzlabs.in/subdomains/viewer) | 🟢 Easy | 🎓 Training | Not Solved | [View](source-code-viewer-basic-curl-ssrf.md) |
| 211 | [Screenshot Tool - URL to Image](https://kzlabs.in/subdomains/capture) | 🟢 Easy | 🎓 Training | Not Solved | [View](screenshot-tool-url-to-image.md) |
| 212 | [Port-based Timing Attack](https://kzlabs.in/subdomains/scanner) | 🟡 Medium | 🎓 Training | Not Solved | [View](port-based-timing-attack.md) |
| 213 | [Domain Restriction Bypass with Redirects](https://kzlabs.in/subdomains/fetch) | 🟡 Medium | 🎓 Training | Not Solved | [View](domain-restriction-bypass-with-redirects.md) |
| 214 | [Website Checker with IP Blacklist](https://kzlabs.in/subdomains/monitor) | 🟡 Medium | 🎓 Training | Not Solved | [View](website-checker-with-ip-blacklist.md) |
| 215 | [AWS Metadata Filter Bypass](https://kzlabs.in/subdomains/cloud) | 🟡 Medium | 🎓 Training | Not Solved | [View](aws-metadata-filter-bypass.md) |
| 216 | [PDF Generator - URL to PDF](https://kzlabs.in/subdomains/print) | 🟢 Easy | 🎓 Training | Not Solved | [View](pdf-generator-url-to-pdf.md) |

### XML External Entity

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 217 | [XML External Entity (XXE) via URL](https://kzlabs.in/subdomains/xml) | 🟢 Easy | 🎓 Training | Not Solved | [View](xml-external-entity-xxe-via-url.md) |
| 218 | [XXE via XML Registration API - SecureVault Password Manager](https://kzlabs.in/subdomains/register) | 🟡 Medium | 🎓 Training | Not Solved | [View](xxe-via-xml-registration-api-securevault-password-manager.md) |
| 219 | [XXE via XML Login API - SecureVault Password Manager](https://kzlabs.in/subdomains/auth-api) | 🟡 Medium | 🎓 Training | Not Solved | [View](xxe-via-xml-login-api-securevault-password-manager.md) |
| 220 | [XXE on Twitter SMS SXMP API (File Read via operatorId Error Reflection)](https://kzlabs.in/subdomains/sms) | 🟡 Medium | 🌐 Real World | Not Solved | [View](xxe-on-twitter-sms-sxmp-api-file-read-via-operatorid-error-reflection.md) |
| 221 | [LFI + SSRF via XXE in SVG Emblem Editor (Rockstar Games ImageMagick)](https://kzlabs.in/subdomains/designer) | 🔴 Hard | 🌐 Real World | Not Solved | [View](lfi-ssrf-via-xxe-in-svg-emblem-editor-rockstar-games-imagemagick.md) |
| 222 | [Blind XXE via JPEG XMP Metadata Injection (Informatica OOB Exfiltration)](https://kzlabs.in/subdomains/images) | 🔴 Hard | 🌐 Real World | Not Solved | [View](blind-xxe-via-jpeg-xmp-metadata-injection-informatica-oob-exfiltration.md) |
| 223 | [XXE via XML Resume Upload Starbucks China Career Portal (IIS + ASP.NET)](https://kzlabs.in/subdomains/careers-api) | 🟡 Medium | 🌐 Real World | Not Solved | [View](xxe-via-xml-resume-upload-starbucks-china-career-portal-iis-asp-net.md) |

### HTTP Request Smuggling

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 224 | [HTTP Request Smuggling](https://kzlabs.in/subdomains/smuggling) | 🟢 Easy | 🎓 Training | Not Solved | [View](http-request-smuggling.md) |

### Cache Poisoning

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 225 | [Cache Poisoning](https://kzlabs.in/subdomains/poisoning) | 🟢 Easy | 🎓 Training | Not Solved | [View](cache-poisoning.md) |

### Business Logic Vulnerabilities

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 226 | [Business Logic Vulnerability](https://kzlabs.in/subdomains/image-api) | 🟢 Easy | 🎓 Training | Not Solved | [View](business-logic-vulnerability.md) |

### File Upload Vulnerabilities

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 227 | [File Upload Vulnerabilities](https://kzlabs.in/subdomains/file-upload-api) | 🟢 Easy | 🎓 Training | Not Solved | [View](file-upload-vulnerabilities.md) |

### Subdomain Takeovers

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 228 | [Subdomain Takeovers](https://vulnera.xyz/) | 🟢 Easy | 🎓 Training | Not Solved | [View](subdomain-takeovers.md) |

### Remote File Inclusion

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 229 | [Remote File Inclusion via URL](https://kzlabs.in/subdomains/include) | 🟢 Easy | 🎓 Training | Not Solved | [View](remote-file-inclusion-via-url.md) |
| 230 | [RFI + XSS + SSRF via Unvalidated URL Proxy in GIS Portal (U.S. DoD)](https://kzlabs.in/subdomains/maps) | 🟡 Medium | 🌐 Real World | Not Solved | [View](rfi-xss-ssrf-via-unvalidated-url-proxy-in-gis-portal-u-s-dod.md) |
| 231 | [PageForge CMS - Content Manager Remote & Local File Inclusion](https://kzlabs.in/subdomains/pages) | 🟡 Medium | 🎓 Training | Not Solved | [View](pageforge-cms-content-manager-remote-and-local-file-inclusion.md) |
| 232 | [ShopStream - E-Commerce Bulk Product Import Remote & Local File Inclusion](https://kzlabs.in/subdomains/import) | 🟡 Medium | 🎓 Training | Not Solved | [View](shopstream-e-commerce-bulk-product-import-remote-and-local-file-inclusion.md) |
| 233 | [StreamFlux - Video Analytics CDN Origin Asset Proxy Remote & Local File Inclusion](https://kzlabs.in/subdomains/origin) | 🟡 Medium | 🎓 Training | Not Solved | [View](streamflux-video-analytics-cdn-origin-asset-proxy-remote-and-local-file-inclusion.md) |

### Special Vulnerabilities

| Lab | Lab Name | Difficulty | Category | Status | Report |
|---:|---|:---:|---|:---:|:---:|
| 234 | [PHP User Authentication & Secure Registration System](https://kzlabs.in/subdomains/authentication) | 🟢 Easy | 🎓 Training | Not Solved | [View](php-user-authentication-and-secure-registration-system.md) |
| 235 | [BookStore - Online Bookstore & Shopping Cart Platform](https://kzlabs.in/subdomains/bookstore) | 🟡 Medium | 🎓 Training | Not Solved | [View](bookstore-online-bookstore-and-shopping-cart-platform.md) |
| 236 | [Burger Palace - Fast Food Restaurant Portal](https://kzlabs.in/subdomains/burger) | 🟢 Easy | 🎓 Training | Not Solved | [View](burger-palace-fast-food-restaurant-portal.md) |
| 237 | [Club Manager - Membership & Events Management Portal](https://kzlabs.in/subdomains/club) | 🟡 Medium | 🎓 Training | Not Solved | [View](club-manager-membership-and-events-management-portal.md) |
| 238 | [CoWork Space - Shared Office & Meeting Room Booking System](https://kzlabs.in/subdomains/coworkingspace) | 🟡 Medium | 🎓 Training | Not Solved | [View](cowork-space-shared-office-and-meeting-room-booking-system.md) |
| 239 | [Employee Management CRUD System](https://kzlabs.in/subdomains/crud) | 🟢 Easy | 🎓 Training | Not Solved | [View](employee-management-crud-system.md) |
| 240 | [DocVault - Enterprise Document Management System](https://kzlabs.in/subdomains/docvault) | 🟡 Medium | 🎓 Training | Not Solved | [View](docvault-enterprise-document-management-system.md) |
| 241 | [Restaurant El Paso - Dining & Table Reservations Portal](https://kzlabs.in/subdomains/elpaso) | 🟢 Easy | 🎓 Training | Not Solved | [View](restaurant-el-paso-dining-and-table-reservations-portal.md) |
| 242 | [English Learning & Vocabulary Portal](https://kzlabs.in/subdomains/english) | 🟢 Easy | 🎓 Training | Not Solved | [View](english-learning-and-vocabulary-portal.md) |
| 243 | [Enigma - College Symposium & Event Management Platform](https://kzlabs.in/subdomains/event) | 🟡 Medium | 🎓 Training | Not Solved | [View](enigma-college-symposium-and-event-management-platform.md) |
| 244 | [Food Order CMS & Restaurant System](https://kzlabs.in/subdomains/food) | 🟡 Medium | 🎓 Training | Not Solved | [View](food-order-cms-and-restaurant-system.md) |
| 245 | [Food Ordering & POS Restaurant Management System](https://kzlabs.in/subdomains/food-ordering) | 🟡 Medium | 🎓 Training | Not Solved | [View](food-ordering-and-pos-restaurant-management-system.md) |
| 246 | [FoodDelivery - Online Food Ordering & Cart Platform](https://kzlabs.in/subdomains/fooddelivery) | 🟡 Medium | 🎓 Training | Not Solved | [View](fooddelivery-online-food-ordering-and-cart-platform.md) |
| 247 | [Foodie - Gourmet Burger Bar & Table Reservation Platform](https://kzlabs.in/subdomains/foodie) | 🟡 Medium | 🎓 Training | Not Solved | [View](foodie-gourmet-burger-bar-and-table-reservation-platform.md) |
| 248 | [Buffet Box - Digital QR Menu & Cloud Kitchen POS](https://kzlabs.in/subdomains/foodmenu) | 🟡 Medium | 🎓 Training | Not Solved | [View](buffet-box-digital-qr-menu-and-cloud-kitchen-pos.md) |
| 249 | [GiftStore - Online Gifts & Souvenirs Portal](https://kzlabs.in/subdomains/gift) | 🟢 Easy | 🎓 Training | Not Solved | [View](giftstore-online-gifts-and-souvenirs-portal.md) |
| 250 | [Grecko - Mediterranean Bar & Seafood Restaurant](https://kzlabs.in/subdomains/grecko) | 🟡 Medium | 🎓 Training | Not Solved | [View](grecko-mediterranean-bar-and-seafood-restaurant.md) |
| 251 | [Grilli - Fine Dining Restaurant & Chef Specials](https://kzlabs.in/subdomains/grilli) | 🟢 Easy | 🎓 Training | Not Solved | [View](grilli-fine-dining-restaurant-and-chef-specials.md) |
| 252 | [Hospital Management System (HMS) - Multi-Portal Healthcare](https://kzlabs.in/subdomains/hms) | 🔴 Hard | 🎓 Training | Not Solved | [View](hospital-management-system-hms-multi-portal-healthcare.md) |
| 253 | [Internship & Student Placement Management System](https://kzlabs.in/subdomains/internship) | 🟡 Medium | 🎓 Training | Not Solved | [View](internship-and-student-placement-management-system.md) |
| 254 | [Johnny's Dining & Bar - Restaurant POS & Management](https://kzlabs.in/subdomains/johnnys) | 🟡 Medium | 🎓 Training | Not Solved | [View](johnnys-dining-and-bar-restaurant-pos-and-management.md) |
| 255 | [Krables - Multi-Vendor E-Commerce Platform](https://kzlabs.in/subdomains/krables) | 🟡 Medium | 🎓 Training | Not Solved | [View](krables-multi-vendor-e-commerce-platform.md) |
| 256 | [Management Lab - Resource & Laboratory Booking Portal](https://kzlabs.in/subdomains/management) | 🟡 Medium | 🎓 Training | Not Solved | [View](management-lab-resource-and-laboratory-booking-portal.md) |
| 257 | [Picture Perfect - Real Estate & Property Showcase](https://kzlabs.in/subdomains/pictureperfect) | 🟢 Easy | 🎓 Training | Not Solved | [View](picture-perfect-real-estate-and-property-showcase.md) |
| 258 | [Planet - CSP Protected Content Security Bypass](https://kzlabs.in/subdomains/planet) | 🔴 Hard | 🎓 Training | Not Solved | [View](planet-csp-protected-content-security-bypass.md) |
| 259 | [RainyRoof - Roofing Services & Quotation Portal](https://kzlabs.in/subdomains/rainyroof) | 🟢 Easy | 🎓 Training | Not Solved | [View](rainyroof-roofing-services-and-quotation-portal.md) |
| 260 | [Rate Limiting & Brute Force Protection Defense Lab](https://kzlabs.in/subdomains/rate-limiting) | 🟡 Medium | 🎓 Training | Not Solved | [View](rate-limiting-and-brute-force-protection-defense-lab.md) |
| 261 | [ReadSphere - Book Review & Community Library Platform](https://kzlabs.in/subdomains/readsphere) | 🔴 Hard | 🎓 Training | Not Solved | [View](readsphere-book-review-and-community-library-platform.md) |
| 262 | [Vincent Pizza - Authentic Italian Restaurant & Ordering](https://kzlabs.in/subdomains/restaurant) | 🟡 Medium | 🎓 Training | Not Solved | [View](vincent-pizza-authentic-italian-restaurant-and-ordering.md) |
| 263 | [Space - Content Security Policy (CSP) Bypass Lab](https://kzlabs.in/subdomains/space) | 🔴 Hard | 🎓 Training | Not Solved | [View](space-content-security-policy-csp-bypass-lab.md) |
| 264 | [EduPro - Student & Academic Management System](https://kzlabs.in/subdomains/student) | 🟡 Medium | 🎓 Training | Not Solved | [View](edupro-student-and-academic-management-system.md) |
| 265 | [ET LAB - Student & College Administration Portal](https://kzlabs.in/subdomains/studentportal) | 🟡 Medium | 🎓 Training | Not Solved | [View](et-lab-student-and-college-administration-portal.md) |
| 266 | [Tour & Travel Vacation Booking Portal](https://kzlabs.in/subdomains/tour) | 🟢 Easy | 🎓 Training | Not Solved | [View](tour-and-travel-vacation-booking-portal.md) |
| 267 | [TripTrip - Tour Agency & Travel Booking Portal](https://kzlabs.in/subdomains/triptrip) | 🟡 Medium | 🎓 Training | Not Solved | [View](triptrip-tour-agency-and-travel-booking-portal.md) |
| 268 | [University Academic & Admissions Portal](https://kzlabs.in/subdomains/university) | 🟡 Medium | 🎓 Training | Not Solved | [View](university-academic-and-admissions-portal.md) |
| 269 | [WebFilesDesk - Self-Hosted File Explorer & Manager](https://kzlabs.in/subdomains/webfiles) | 🟡 Medium | 🎓 Training | Not Solved | [View](webfilesdesk-self-hosted-file-explorer-and-manager.md) |
| 270 | [Yummy - Food Delivery & Restaurant Platform](https://kzlabs.in/subdomains/yummy) | 🟡 Medium | 🎓 Training | Not Solved | [View](yummy-food-delivery-and-restaurant-platform.md) |
| 271 | [ControlHub - JSON Response Manipulation Auth Bypass](https://kzlabs.in/subdomains/hub) | 🔴 Hard | 🎓 Training | Not Solved | [View](controlhub-json-response-manipulation-auth-bypass.md) |
| 272 | [VaultTech - JWT Token Credential Reuse Across Admin Panels](https://kzlabs.in/subdomains/vault) | 🔴 Hard | 🎓 Training | Not Solved | [View](vaulttech-jwt-token-credential-reuse-across-admin-panels.md) |
| 273 | [CloudSync - PII Leaked on Unauthorized File](https://kzlabs.in/subdomains/sync) | 🔴 Hard | 🎓 Training | Not Solved | [View](cloudsync-pii-leaked-on-unauthorized-file.md) |
| 274 | [CBSE - Default Credentials Authentication Bypass](https://kzlabs.in/subdomains/school) | 🔴 Hard | 🎓 Training | Not Solved | [View](cbse-default-credentials-authentication-bypass.md) |
| 275 | [Aliyun WAF Bypass - Bypass WAF Rules](https://kzlabs.in/subdomains/shield) | 🔴 Hard | 🎓 Training | Not Solved | [View](aliyun-waf-bypass-bypass-waf-rules.md) |
| 276 | [Aliyun WAF Bypass - Bypass WAF Rules](https://kzlabs.in/subdomains/blog) | 🔴 Hard | 🎓 Training | Not Solved | [View](aliyun-waf-bypass-bypass-waf-rules.md) |
| 277 | [Aliyun WAF Bypass](https://kzlabs.in/subdomains/kzlabs) | 🔴 Hard | 🎓 Training | Not Solved | [View](aliyun-waf-bypass.md) |
| 278 | [Unrestricted File Upload - PHP Profile Picture Leads to Remote Code Execution](https://kzlabs.in/subdomains/avatar) | 🔴 Hard | 🎓 Training | Not Solved | [View](unrestricted-file-upload-php-profile-picture-leads-to-remote-code-execution.md) |
