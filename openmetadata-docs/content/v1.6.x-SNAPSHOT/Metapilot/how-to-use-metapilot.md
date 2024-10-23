---
title: How to Use MetaPilot
slug: /metapilot/how-to-use-metapilot
collate: true
---

# How to Use MetaPilot

## 1. Setting Up MetaPilot
- Navigate to **Settings > Applications** in the Collate platform.

{% image
src="/images/v1.6/metapilot/setting-up-metapilot-1.png"
alt="setting up metapilot"
caption="Navigate to Settings > Applications"
/%}

- Install MetaPilot by following the on-screen instructions.

{% image
src="/images/v1.6/metapilot/setting-up-metapilot-2.png"
alt="Install MetaPilot"
caption="Install MetaPilot"
/%}

- Select the databases for which you want MetaPilot to automatically generate descriptions. You can configure multiple databases and set a default database for the MetaPilot chatbot to work with.

{% image
src="/images/v1.6/metapilot/setting-up-metapilot-3.png"
alt="automatically generate descriptions"
caption="automatically generate descriptions"
/%}

- **Scheduling**: Schedule MetaPilot to run regularly, automatically generating metadata at predefined intervals (e.g., weekly).

{% image
src="/images/v1.6/metapilot/setting-up-metapilot-4.png"
alt="Schedule MetaPilot"
caption="Schedule MetaPilot"
/%}

## 2. Using the MetaPilot Chatbot
- The MetaPilot chatbot icon appears on every page after installation.

{% image
src="/images/v1.6/metapilot/using-metapilot-chatbot-1.png"
alt="chatbot icon"
caption="chatbot icon"
/%}

- Interact with the chatbot by typing natural language questions. For example:
  - “Show me sales data for Q1.”
  - “What is the average revenue per customer?”

- MetaPilot will generate the corresponding SQL query and provide a detailed explanation of the query logic.

{% image
src="/images/v1.6/metapilot/using-metapilot-chatbot-2.png"
alt="natural language questions"
caption="natural language questions"
/%}

- Users can refine queries by providing further instructions, and the chatbot will adjust the SQL query accordingly.

## 3. Optimizing and Fixing SQL Queries

- The **Metadata Usage** workflows will ingest the queries being run against the tables. You can see how long each query has been executed in the **Queries** tab.

{% image
src="/images/v1.6/metapilot/fixing-sql-queries-1.png"
alt="metadata usage workflows"
caption="metadata usage workflows"
/%}

- If a query runs inefficiently, ask the chatbot to optimize it by typing: “Optimize this query.”

{% image
src="/images/v1.6/metapilot/fixing-sql-queries-3.png"
alt="Optimize this query"
caption="Optimize this query"
/%}

- MetaPilot will return a more efficient version of the SQL query, which you can then copy and execute in your database.

- If the query contains errors or isn’t functioning correctly, ask MetaPilot: “Can you fix this query?” 

- MetaPilot will correct the query and provide a working version.

{% image
src="/images/v1.6/metapilot/fixing-sql-queries-4.png"
alt="Can you fix this query"
caption="Can you fix this query"
/%}

## 4. Reviewing Generated Metadata
- Once MetaPilot generates descriptions for tables and columns, navigate to the **database view** to review the metadata.
- You can accept or reject each suggestion individually or choose to accept all suggestions in bulk.

{% image
src="/images/v1.6/metapilot/reviewing-generated-metadata.png"
alt="reviewing Generated Metadata"
caption="reviewing Generated Metadata"
/%}

- MetaPilot allows you to document entire datasets in a matter of minutes, significantly reducing the manual effort required to maintain metadata.

## Best Practices
- **Regular Scheduling**: Schedule MetaPilot to run at regular intervals to ensure your metadata is always up-to-date, especially when dealing with frequently changing datasets.
- **Leverage the Chatbot for Query Writing**: Encourage both technical and non-technical users to use the MetaPilot chatbot for SQL query generation. It simplifies complex query writing and ensures accurate results.
- **Optimize Queries Regularly**: Monitor the performance of your queries and use MetaPilot to optimize them, especially when working with large datasets or queries that require complex joins and filters.