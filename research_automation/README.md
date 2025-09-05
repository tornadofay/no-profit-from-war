# AI Research Hub for the Demilitarize the Markets Initiative

## 1. Purpose of This Hub

This directory contains instructions and resources for AI agents and Large Language Models (LLMs) to perform automated, continuous research in support of the "Demilitarize the Markets" proposal.

The goal is to keep the project's data, evidence, and case studies up-to-date with minimal manual effort. The research gathered by automated agents should be used to update the main `README.md` of the project and to inform advocacy strategies.

## 2. Core Research Areas

Automated agents should focus on the following areas:

*   **Arms Trade Data:** Monitoring the latest statistics on international arms transfers, military spending, and the financial performance of major arms manufacturers.
*   **Market and Investor Trends:** Tracking news and analysis related to defense stocks, investor sentiment, and any new divestment commitments.
*   **Political and Legal Developments:** Scanning for news related to new arms control treaties, government policies, or statements from influential figures.
*   **Campaign Precedents:** Finding new information or analysis on related campaigns (e.g., fossil fuel divestment, tobacco control).

## 3. Trusted Data Sources

Agents should prioritize information from the following sources:

*   **SIPRI (Stockholm International Peace Research Institute):** `https://www.sipri.org` (for annual reports on arms transfers and military expenditure)
*   **Reuters:** `https://www.reuters.com/business/aerospace-defense/` (for financial news on the defense industry)
*   **Associated Press (AP):** `https://apnews.com/hub/defense`
*   **Human Rights Watch:** `https://www.hrw.org/topic/arms`
*   **Amnesty International:** `https://www.amnesty.org/en/what-we-do/arms-control/`
*   **Major Financial News Outlets:** For quarterly earnings reports of top defense contractors (e.g., Lockheed Martin, RTX, BAE Systems, Boeing).

## 4. Standard Research Prompts

Here are some example prompts that can be used for automated research tasks.

### Prompt 1: Quarterly Earnings Analysis

"Review the latest quarterly earnings reports for the following companies: [List of top 5 defense contractors]. Extract the following information for each:
1.  Revenue from their defense/military segment.
2.  Year-over-year growth for that segment.
3.  Any quotes from executives regarding future outlook or geopolitical factors influencing their business.
Present the output as a Markdown table."

### Prompt 2: Media Monitoring for Key Terms

"Scan the news from the last 7 days from the trusted sources list for the following keywords: 'arms trade treaty', 'defense stocks', 'divestment military', 'ethical investment'. Summarize any significant articles found. For each summary, include the source, title, and a direct link. If no significant news is found, state that."

### Prompt 3: Annual SIPRI Report Update

"Check the SIPRI website for the latest annual report on global military expenditure or arms transfers. If a new report has been published since the last check, summarize the key findings, focusing on the top 5 exporters/importers and the overall trend in spending. Provide a direct link to the report."

## 5. Desired Output Format

To ensure consistency, all research findings should be formatted in one of the following ways:

*   **Markdown:** For easy readability and integration into GitHub files. Use tables, lists, and clear headings.
*   **JSON:** For structured data that can be easily parsed by other tools. Use clear key-value pairs.

When a research task is complete, the agent should ideally create a new file in a sub-directory (e.g., `/research_automation/output/YYYY-MM-DD_research_summary.md`) to log the findings.

---
This document is a living guide. Contributions and suggestions for new prompts, sources, or methodologies are welcome.
