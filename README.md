# Cherry-Prices
Monitoring Cherry Prices in China

The problem: How can an export company make fast decisions when the price data received from China is in English, Chinese, and technical language, and is very extensive? Additionally, the data arrives at night in South America while the team in China is working.

A strategic analysis revealed that this data is critical because it helps the management decide whether to ship fruit by air or sea (with a cost ratio of 4:1), among other key decisions that significantly impact the company’s P&L.

The solution implemented combines automation, large language models (LLMs), and Power BI. When the email containing complex price data from China arrives, it triggers an automation workflow using N8N. An LLM (GEMINI), guided by a structured and trained prompt, extracts and normalizes the data. The processed data is then uploaded to an SFTP server, where it is visualized through a Power BI dashboard that calculates margins and production costs.

This process updates every 4 minutes after receiving the email, eliminating the need for experts to spend hours creating databases and reports. As a result, the company can make timely, data-driven decisions whenever needed.

[![Cherry Prices](https://img.youtube.com/vi/Hkg9Eotzg_w/0.jpg)](https://www.youtube.com/watch?v=Hkg9Eotzg_w)
