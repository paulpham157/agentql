<div align="center">

<h1 align="center">
    <a href="https://agentql.com">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/972700ef-b4e6-49e9-a282-40994d9cb823">
          <img alt="AgentQL" src="https://github.com/user-attachments/assets/893d8117-258c-4cf9-8fd8-5c850586e8d4" width="500">
        </picture>
    </a>
</h1>

<h2>AgentQL connects LLMs and AI agents to the entire web</h2>

<p align="center">
  <a href="https://twitter.com/agentql"><img src="https://img.shields.io/badge/Follow%20on%20X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X" /></a>
  <a href="https://www.linkedin.com/company/tinyfish-ai"><img src="https://img.shields.io/badge/Follow%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Follow on LinkedIn" /></a>
  <a href="https://discord.gg/agentql"><img src="https://img.shields.io/badge/Join%20our%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join our Discord" /></a>
</p>

<p align="center">
  <a href="https://pypi.org/project/agentql"><img src="https://img.shields.io/pypi/v/agentql" alt="Python version" /></a>
  <a href="#repository-details-container"><img src="https://img.shields.io/github/stars/tinyfish-io/agentql" alt="GitHub Repo stars" /></a>
  <a href="#repository-details-container"><img src="https://img.shields.io/github/watchers/tinyfish-io/agentql" alt="GitHub watchers" /></a>
</p>

</div>

## What is AgentQL?

AgentQL is a suite of tools for extracting data and automating workflows on live web sites featuring an AI-powered query language, Python and JavaScript SDKs, a browser-based debugger, and a REST API endpoint. It uses natural language queries to pinpoint data and elements on any web page, including authenticated and dynamically generated content. Users can define structured data output and apply transforms within queries. AgentQL's natural language selectors find elements intuitively based on the content of the web page and work across similar web sites, self-healing as UI changes over time.

[Get started in 5 minutes with our quick start!](https://docs.agentql.com/quick-start)

### Features

- **Playwright** [AgentQL's Python SDK](https://docs.agentql.com/python-sdk/installation) and [JavaScript SDK](https://docs.agentql.com/javascript-sdk/installation) seamlessly integrates with Playwright for advanced automation and testing.
- **Cross-site compatibility** lets you use the same query across different sites with similar content.
- **Structured output** defined by the shape of your query.
- **Natural language selectors** find elements and data anywhere on a site using intuitive queries.
- **Transforms _and_ extracts** data in your queries.
- **Works on any page,** public or private, any site, any URL, even behind authentication.
- **Resiliance to UI changes** means queries work regardless of how a page's structure changes over time.

### Tools

- **[Python SDK](https://docs.agentql.com/python-sdk/installation)** for running automation and scraping scripts with AgentQL queries in Python.
- **[JavaScript SDK](https://docs.agentql.com/javascript-sdk/installation)** for running automation and scraping scripts with AgentQL queries in JavaScript.
- **[REST API](https://docs.agentql.com/rest-api/api-reference)** for executing queries without an SDK.
- **[Integrations](https://docs.agentql.com/integrations)** with agent frameworks and automation tools like Langchain and Zapier and our MCP server.
- **[Debugger Browser Extension](https://chromewebstore.google.com/detail/agentql-debugger/idnejmodeepdobpinkkgpkeabkabhhej)** lets you debug and finesse queries in real-time on live sites.
- **[AgentQL Query Language](https://docs.agentql.com/agentql-query/query-intro)** lets you define queries with natural language.
- **[Playground](https://playground.agentql.com/)** for playing with AgentQL lets you export python scripts and optimize queries with prompts.

## Examples

| Example Name                            | Python                                                                                                                                                                                                                                        | JavaScript                                                                                                        |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| Getting Started                         | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/first_steps)                                                                                                                                                        | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/first-steps)                                |
| Close Cookie Dialog                     | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/close_cookie_dialog) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/close_cookie_dialog)                                           | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/close-cookie-dialog)                        |
| Close Popup Windows                     | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/close_popup) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/close_popup)                                                           | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/close-popup)                                |
| Compare Product Prices                  | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/compare_product_prices) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/compare_product_prices)                                     | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/compare-product-prices)                     |
| Get Element by Prompt                   | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/get_by_prompt)                                                                                                                                                      | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/get-by-prompt)                              |
| Infinite Scroll                         | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/infinite_scroll) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/infinite_scroll)                                                   | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/infinite-scroll)                            |
| Use Remote Browser                    | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/use_remote_browser)                                                                                                                         | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/use-remote-browser) |
| Use Existing Browser                    | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/use_existing_browser)                                                                                                                         | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/use-existing-browser) |
| Query List Items                        | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/list_query_usage)                                                                                                                                                   | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/list-query-usage)                           |
| Site Login                              | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/log_into_sites) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/log_into_sites)                                                     | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/log-into-sites)                             |
| Headless Browser                        | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/run_script_in_headless_browser) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/run_script_in_headless_browser)                     | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/run-script-in-headless-browser)             |
| Save/Load Auth Session                  | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/save_and_load_authenticated_session)                                                                                                                                | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/save-and-load-authenticated-session)        |
| Stealth Mode                            | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/stealth_mode)                                                                                                                                                       | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/stealth-mode)                               |
| Wait for Page Load                      | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/wait_for_entire_page_load) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/wait_for_entire_page_load)                               | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/wait-for-entire-page-load)                  |
| E-commerce Pricing Data                 | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/collect_ecommerce_pricing_data)                                                                                                                                     | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/collect-pricing-data)                       |
| Sentiment Analysis                      | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/perform_sentiment_analysis) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/perform_sentiment_analysis)                             | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/perform-sentiment-analysis)                 |
| Get XPath                               | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/xpath)                                                                                                                                                              | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/xpath)                                      |
| Submit Form                             | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/submit_form)                                                                                                                                                        | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/submit-form)                                |
| Collect YouTube Comments                | N/A                                                                                                                                                                                                                                           | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/collect-youtube-comments)                   |
| Use Humanlike Behavior to Avoid Antibot | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/humanlike-antibot)                                                                                                                                                  | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/humanlike-antibot)                          |
| Run in Google Colab                     | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/run_script_online_in_google_colab)                                                                                                                                  | N/A                                                                                                               |
| Collect Ecommerce Paginated Data        | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/collect_paginated_ecommerce_listing_data) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/collect_paginated_ecommerce_listing_data) | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/collect-paginated-ecommerce-data)           |
| Collect Paginated Data From HackerNews  | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/collect_paginated_news_headlines) / [Colab](https://github.com/tinyfish-io/agentql/tree/main/examples/googlecolab/collect_paginated_news_headlines)                 | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/collect-paginated-news-headlines)           |
| Scrape Google Maps and save as a CSV    | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/maps_scraper)                                                                                                                                                       | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/maps_scraper)                               |
| News Aggregator                         | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/python/news-aggregator)                                                                                                                                                    | [Script](https://github.com/tinyfish-io/agentql/tree/main/examples/js/news-aggregator)                            |

For comprehensive guides and API references, check out our [official documentation](https://docs.agentql.com).

## Show Your Support 🌟

If you find AgentQL helpful, please consider giving us a star on GitHub! It helps us reach more developers and continue improving the project.

<div align="center">
  <a href="#repository-details-container"><img src="https://img.shields.io/github/stars/tinyfish-io/agentql" alt="GitHub Repo stars" /></a>
</div>

## Get in touch

For questions, feedback, or support, join our [Discord community](https://discord.gg/agentql). You can follow us on [GitHub](https://github.com/tinyfish-io/), [Twitter](https://x.com/AgentQL), and [LinkedIn](https://www.linkedin.com/company/95728009)!
