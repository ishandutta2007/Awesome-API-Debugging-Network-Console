# Awesome-API-Debugging-Network-Console

A curated directory and comparison of API debugging tools, HTTP/HTTPS intercepting proxies, network packet analyzers, and developer consoles.

---

## Sector Overview & Market Dynamics

The global API management and developer observability tooling market is valued at approximately **$8.8B to $10.0B** (projected to reach over $13.5B by 2026 at a ~20–30% CAGR). The broader sector is **moderately concentrated at the enterprise infrastructure and gateway tier** (dominated by hyperscalers and platforms like Google Apigee, Kong, Postman, and MuleSoft), while remaining **highly fragmented at the developer debugging, local proxy, and network inspection tier**, where an active ecosystem of specialized commercial utilities, bootstrapped micro-ISVs, and community open-source projects co-exist.

---

## Commercial & SaaS Products

The table below covers the commercial and SaaS tools across the API debugging, proxying, and network console landscape. Sorted descending by company size (valuation / revenue).

| Product | Company / Parent | Company Size (Valuation / Revenue) | Starting Pricing (Paid Tier) | Free Tier Limits / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Postman Console** | Postman Inc. | **$5.6B valuation** (~$300M ARR) | $9/user/month (Solo, billed annually) or $19/user/month (Team) | **Free forever plan:** 1 user workspace, core API testing/debugging, 50 AI credits, 1,000 Context Graph queries/mo; collaboration restricted | Collaborative API design, testing, mock servers, and in-console network request inspection. |
| **Requestly** | BrowserStack *(acquired)* | **$4.0B valuation** (~$225M–$300M Parent ARR) | $12/user/month (Lite, billed annually) or $25/user/month (Pro) | **Free forever plan:** 1 user, essential HTTP rule creation, header modification, and redirect rules with capped mock data / shared lists | Chrome extension and desktop proxy for intercepting, modifying, and redirecting HTTP requests without network proxies. |
| **Insomnia** | Kong Inc. | **$2.0B valuation** (~$100M+ ARR) | $10/user/month (Pro, billed annually) | **Free forever plan:** Up to 3 users for Git Sync projects, unlimited cloud/local projects, 1,000 mock requests/mo, local offline Scratch Pad | Streamlined REST, GraphQL, and gRPC client with built-in network traffic inspection and environment sync. |
| **Fiddler Everywhere** | Progress Software *(NASDAQ: PRGS)* | **$1.8B market cap** (~$1.0B Parent Revenue) | $12/user/month (Pro, billed annually) or $18/month (billed monthly) | **10-day free trial:** Fully functional with unrestricted enterprise features, rule sets, and cloud captures; requires paid plan upon expiration | Modern cross-platform web debugging proxy for macOS, Windows, and Linux with traffic inspection and composition. |
| **Proxyman** | Proxyman LLC | **~$900K ARR** (Bootstrapped indie ISV) | $89–$99 one-time perpetual license (includes 1 year of updates) | **Free forever tier:** Single user, restricted to 1 active debugging rule (SSL Proxying/Map Local/Breakpoints) and 2 pinned domains; commercial trial limited to 14 days | Native, high-performance macOS/Windows/Linux HTTP/HTTPS debugging proxy with scriptable rule sets and iOS/Android companion apps. |
| **Charles Proxy** | XK72 Ltd. | Bootstrapped ISV / Micro-business *(Private, not disclosed)* | $50 one-time perpetual license (single seat; volume/multi-site discounts available) | **30-day free trial:** Fully featured; post-trial unlicensed sessions automatically terminate and force-quit after 30 minutes of continuous use | Classical cross-platform Java-based HTTP proxy, reverse proxy, and bandwidth throttling tool. |

---

## Open Source & Community Tooling

In addition to commercial platforms, key network analysis and debugging utilities include:

* **[Wireshark](https://www.wireshark.org/)** — Open Source (GPLv2+). The de-facto industry standard for packet inspection and protocol analysis operating at the transport/network layer.
* **[mitmproxy](https://mitmproxy.org/)** — Open Source (MIT). An interactive, SSL/TLS-capable intercepting HTTP proxy with a console UI (`mitmproxy`), web UI (`mitmweb`), and Python scripting API.
* **[Whistle](https://wproxy.org/whistle/)** — Open Source (Node.js). Cross-platform web debugging tool based on Node.js supporting HTTP, HTTPS, WebSocket, and TCP capture and modification.
* **[Chrome DevTools](https://developer.chrome.com/docs/devtools/)** — Integrated into Chromium/Blink-based browsers. Real-time network tab capturing waterfall timings, request/response headers, WebSockets, and payload inspections.
