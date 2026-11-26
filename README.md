# EVP Labs Data Extractors

Open source quick-start kits for the published Apify scrapers maintained by EVP Labs. Each repository includes Python and Node.js examples, MCP configuration, a real sanitized sample dataset, and an n8n workflow template.

The searchable documentation site is available at [intius.github.io/evp-labs-data-extractors](https://intius.github.io/evp-labs-data-extractors/). It includes per-Actor quick inputs, ready-made task links, integration options, and sample records.

## Live Apify Actors

| Actor | Apify Actor | Developer kit | What it extracts |
|---|---|---|---|
| [WordPress Plugin Directory Scraper](https://apify.com/evpp/wordpress-plugin-directory) | [`evpp/wordpress-plugin-directory`](https://apify.com/evpp/wordpress-plugin-directory) | [`evp-wordpress-plugin-directory-scraper`](https://github.com/intius/evp-wordpress-plugin-directory-scraper) | Extract data on 76,000+ WordPress.org plugins: installs, ratings, versions, authors, tags, and update history via the official public API. |
| [Zapier App Directory Scraper](https://apify.com/evpp/zapier-app-directory) | [`evpp/zapier-app-directory`](https://apify.com/evpp/zapier-app-directory) | [`evp-zapier-app-directory-scraper`](https://github.com/intius/evp-zapier-app-directory-scraper) | Export all 10,500+ Zapier integrations - names, categories, usage counts, domains - as clean JSON in seconds. |
| [Atlassian Marketplace Scraper](https://apify.com/evpp/atlassian-marketplace) | [`evpp/atlassian-marketplace`](https://apify.com/evpp/atlassian-marketplace) | [`evp-atlassian-marketplace-scraper`](https://github.com/intius/evp-atlassian-marketplace-scraper) | Extract Jira and Confluence app listings, vendors, installs, ratings and pricing models from the Atlassian Marketplace API. |
| [VS Code Marketplace Scraper](https://apify.com/evpp/vscode-marketplace) | [`evpp/vscode-marketplace`](https://apify.com/evpp/vscode-marketplace) | [`evp-vscode-marketplace-scraper`](https://github.com/intius/evp-vscode-marketplace-scraper) | Pull VS Code extension data - installs, ratings, versions, publishers - via Microsoft's public gallery API. |
| [Apple Podcasts Charts & Search Scraper](https://apify.com/evpp/apple-podcasts-charts) | [`evpp/apple-podcasts-charts`](https://apify.com/evpp/apple-podcasts-charts) | [`evp-apple-podcasts-charts-scraper`](https://github.com/intius/evp-apple-podcasts-charts-scraper) | Scrape Apple Podcasts top charts, genre charts, and search results with RSS feed URLs, via public Apple JSON endpoints. |
| [Steam Game Intelligence Scraper](https://apify.com/evpp/steam-game-intel) | [`evpp/steam-game-intel`](https://apify.com/evpp/steam-game-intel) | [`evp-steam-game-intel-scraper`](https://github.com/intius/evp-steam-game-intel-scraper) | Pull Steam owners estimates, concurrent players, review scores, pricing, and release data for any game via public Steam + SteamSpy JSON endpoints. |
| [Grants.gov Scraper](https://apify.com/evpp/grants-gov) | [`evpp/grants-gov`](https://apify.com/evpp/grants-gov) | [`evp-grants-gov-scraper`](https://github.com/intius/evp-grants-gov-scraper) | Monitor US federal funding opportunities from Grants.gov: award ceilings, eligibility, CFDA numbers and deadlines via the public JSON API. |
| [USAspending Federal Awards Scraper](https://apify.com/evpp/usaspending) | [`evpp/usaspending`](https://apify.com/evpp/usaspending) | [`evp-usaspending-scraper`](https://github.com/intius/evp-usaspending-scraper) | Scrape US federal contract, grant and loan awards from the official USAspending API. Filter by contractor, agency, amount and date; enriched with NAICS, CFDA and recipient location. |
| [ClinicalTrials.gov Scraper](https://apify.com/evpp/clinicaltrials-gov) | [`evpp/clinicaltrials-gov`](https://apify.com/evpp/clinicaltrials-gov) | [`evp-clinicaltrials-gov-scraper`](https://github.com/intius/evp-clinicaltrials-gov-scraper) | Search ClinicalTrials.gov by keyword, condition, sponsor, status, or country and get clean flat JSON of trials, sponsors, phases, enrollment, sites, and outcomes via the official API. |
| [SEC EDGAR Filings Scraper](https://apify.com/evpp/sec-edgar-filings) | [`evpp/sec-edgar-filings`](https://apify.com/evpp/sec-edgar-filings) | [`evp-sec-edgar-filings-scraper`](https://github.com/intius/evp-sec-edgar-filings-scraper) | Search and monitor SEC EDGAR filings via official JSON APIs: full-text search across all filers or per-company feeds by ticker/CIK, with direct document URLs. |
| [Y Combinator Companies Scraper](https://apify.com/evpp/yc-companies) | [`evpp/yc-companies`](https://apify.com/evpp/yc-companies) | [`evp-yc-companies-scraper`](https://github.com/intius/evp-yc-companies-scraper) | Scrape live YC startups with founder names, titles, LinkedIn/X URLs, public contact emails, careers pages and hiring signals. No browser, no proxy. |
| [Multi-ATS Tech Jobs Scraper - Greenhouse, Ashby & Lever](https://apify.com/evpp/ats-jobs-aggregator) | [`evpp/ats-jobs-aggregator`](https://apify.com/evpp/ats-jobs-aggregator) | [`evp-ats-jobs-aggregator-scraper`](https://github.com/intius/evp-ats-jobs-aggregator-scraper) | Aggregate live tech jobs from 420+ verified Greenhouse, Ashby and Lever boards with salary, remote, department, location and date filters. |
| [Shopify App Store & Developer Leads Scraper](https://apify.com/evpp/shopify-app-store-leads) | [`evpp/shopify-app-store-leads`](https://apify.com/evpp/shopify-app-store-leads) | [`evp-shopify-app-store-leads-scraper`](https://github.com/intius/evp-shopify-app-store-leads-scraper) | Extract Shopify app listings plus developer names, websites, support emails, pricing tiers, ratings, reviews and launch metadata. |
| [Substack Publications, Authors & Sponsorship Leads](https://apify.com/evpp/substack-publications-leads) | [`evpp/substack-publications-leads`](https://apify.com/evpp/substack-publications-leads) | [`evp-substack-publications-leads-scraper`](https://github.com/intius/evp-substack-publications-leads-scraper) | Scrape Substack category leaderboards with publication, author, subscriber tier, paid model, custom domain and sponsorship lead data. |
| [UK Companies House B2B Company Enrichment Scraper](https://apify.com/evpp/companies-house-uk) | [`evpp/companies-house-uk`](https://apify.com/evpp/companies-house-uk) | [`evp-companies-house-uk-scraper`](https://github.com/intius/evp-companies-house-uk-scraper) | Search UK Companies House and enrich companies with status, incorporation date, registered address, company type and public registry links. |

## Use with AI agents

Every kit includes an `mcp-config.json` pointing to the hosted Apify MCP server with the matching Actor preselected. Connect your MCP client, open the kit README, and copy the configuration for the Actor you want to use.

For a multi-source agent, use the [EVP Public Data MCP server](https://github.com/intius/evp-public-data-mcp). It is published in the Official MCP Registry as `io.github.intius/evp-public-data-mcp` and is also available as a one-click Claude Desktop MCPB release.

## Automation

Every kit also includes an importable n8n workflow template for scheduled extraction to a webhook. Apify datasets can also be consumed through the API, Zapier, Make, Python, Node.js, CSV, Excel, or JSON export.

## Machine-readable index

`actors.json` lists every live Actor, its canonical Store page, API integration pages for CLI, JavaScript, MCP, OpenAPI, and Python buyers, published preset task pages, GitHub kit, and direct MCP URL. Use it as a machine-readable routing index for AI agents and automation builders.
