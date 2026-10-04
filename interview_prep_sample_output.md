# AI Interview Preparation Agent — Sample Output

**Pipeline:** Serper web search → Interview Research Analyst → Interview Preparation Coach
**Model:** Llama 3 (Ollama, local) | **Framework:** CrewAI (sequential)
**Inputs:** Software Engineer, Data Analyst

---

# ============================================================
# 💼 INTERVIEW PREP PLAN FOR: Software Engineer
# ============================================================

## Researcher Output (Agent 1)

- Core languages frequently required: Python, Java, JavaScript/TypeScript, C++, Go.
- Data structures and algorithms are tested in almost every screening round (arrays, hash maps, trees, graphs, dynamic programming).
- System design questions appear for mid-level roles and above (scalability, load balancing, caching, databases).
- Commonly mentioned tools: Git, Docker, CI/CD pipelines, REST APIs, SQL/NoSQL databases.
- Behavioral rounds use the STAR method (Situation, Task, Action, Result).
- Job postings emphasize testing, code review, and Agile/Scrum collaboration.
- Cloud familiarity (AWS, Azure, or GCP) is increasingly listed as a requirement.
- Frequently asked questions: reverse a linked list, explain OOP principles, difference between process and thread.

## Role Overview

A Software Engineer designs, builds, tests, and maintains software systems. Day-to-day work includes writing clean code, reviewing teammates' code, debugging production issues, and collaborating with product managers and designers. Interviews typically combine a recruiter screen, one or two coding rounds, a system design round, and a behavioral round.

## Key Skills & Topics to Study

| Area | Topics |
|---|---|
| Programming | One language in depth (Python/Java/C++), OOP, exception handling, memory management |
| DSA | Arrays, strings, linked lists, stacks/queues, hash tables, trees, graphs, sorting/searching, recursion, DP, Big-O analysis |
| Systems & CS Fundamentals | OS basics (processes, threads, deadlocks), networking (HTTP, TCP/IP), concurrency |
| Databases | SQL joins, indexing, normalization, transactions (ACID), basics of NoSQL |
| Engineering Practice | Git workflow, unit testing, CI/CD, code reviews, Agile |
| System Design | Scalability, load balancers, caching, API design, database sharding |
| Soft Skills | Communication, teamwork, ownership, handling conflict |

## Common Interview Questions

1. Explain the four pillars of OOP with real examples.
2. What is the difference between a process and a thread?
3. How would you detect a cycle in a linked list?
4. What is the time complexity of searching in a hash table, and when does it degrade?
5. Explain the difference between SQL and NoSQL databases. When would you choose each?
6. What happens when you type a URL into a browser and press Enter?
7. Design a URL shortener like bit.ly.
8. Tell me about a time you disagreed with a teammate. How did you resolve it?

## 7-Day Preparation Plan

| Day | Focus | Tasks |
|---|---|---|
| **Day 1** | Role & language refresh | Re-read the job description; revise syntax, OOP, and standard library of your main language; solve 3 easy problems |
| **Day 2** | Data structures I | Arrays, strings, hash maps, two-pointer and sliding window patterns; solve 4 problems |
| **Day 3** | Data structures II | Linked lists, stacks, queues, trees, BST traversal; solve 4 problems |
| **Day 4** | Algorithms | Sorting, binary search, recursion, graphs (BFS/DFS), intro to DP; solve 3–4 problems, analyze Big-O for each |
| **Day 5** | CS fundamentals & databases | OS concepts, networking basics, SQL queries, indexing, ACID; write 5 SQL queries |
| **Day 6** | System design & behavioral | Practice one system design (URL shortener); prepare 4 STAR stories |
| **Day 7** | Mock interview & review | Full timed mock (coding + behavioral); review weak areas; prepare questions for the interviewer; rest early |

## Final Tips

- Think out loud — interviewers evaluate your reasoning, not just the final answer.
- Clarify requirements and edge cases before writing code.
- State time and space complexity after every solution.
- Test your code with a small example before saying you're done.
- Prepare 2–3 thoughtful questions about the team, tech stack, and engineering culture.
- If you're stuck, say so and talk through what you've tried instead of staying silent.

---

# ============================================================
# 💼 INTERVIEW PREP PLAN FOR: Data Analyst
# ============================================================

## Researcher Output (Agent 1)

- SQL is the most consistently required skill (joins, aggregations, window functions, subqueries).
- Excel is expected for most roles (pivot tables, VLOOKUP/XLOOKUP, formulas).
- Visualization tools commonly listed: Tableau, Power BI, Looker.
- Python or R for data cleaning and analysis (pandas, NumPy, matplotlib).
- Statistics fundamentals are tested: mean/median, variance, hypothesis testing, p-values, correlation vs causation.
- Interviewers often give case-style or business problems (e.g., "why did sales drop last month?").
- Data cleaning (handling missing values, duplicates, outliers) is a frequent discussion topic.
- Communication of insights to non-technical stakeholders is repeatedly emphasized.

## Role Overview

A Data Analyst collects, cleans, and analyzes data to help the business make better decisions. They write queries, build dashboards, define and track KPIs, and present findings to stakeholders. Interviews usually include a SQL assessment, a statistics/analytics round, a case study or take-home task, and a behavioral round.

## Key Skills & Topics to Study

| Area | Topics |
|---|---|
| SQL | SELECT, JOINs, GROUP BY/HAVING, subqueries, CTEs, window functions (ROW_NUMBER, RANK, LAG/LEAD) |
| Spreadsheets | Pivot tables, lookups, conditional formulas, charts |
| Programming | Python (pandas, NumPy, matplotlib/seaborn) or R |
| Statistics | Descriptive stats, distributions, hypothesis testing, confidence intervals, A/B testing |
| Visualization | Dashboard design in Tableau/Power BI, choosing the right chart, storytelling with data |
| Data Cleaning | Missing values, duplicates, outliers, data validation |
| Business Skills | KPIs, metrics definition, root-cause analysis, stakeholder communication |

## Common Interview Questions

1. What is the difference between INNER JOIN, LEFT JOIN, and FULL OUTER JOIN?
2. How do you handle missing or inconsistent data in a dataset?
3. Explain the difference between correlation and causation.
4. What is a p-value, and how do you interpret it?
5. Write a query to find the top 3 products by revenue in each category.
6. How would you investigate a sudden 20% drop in website traffic?
7. When would you use a bar chart versus a line chart?
8. Describe a time your analysis changed a business decision.

## 7-Day Preparation Plan

| Day | Focus | Tasks |
|---|---|---|
| **Day 1** | Role & business context | Study the company's product and key metrics; review the job description; list the tools mentioned |
| **Day 2** | SQL basics to intermediate | Joins, GROUP BY, HAVING, subqueries; solve 8–10 practice queries |
| **Day 3** | Advanced SQL | CTEs and window functions; solve 5 harder problems (top-N per group, running totals, month-over-month change) |
| **Day 4** | Excel & Python | Pivot tables and lookups; pandas for cleaning, grouping, merging; clean one messy dataset end-to-end |
| **Day 5** | Statistics & A/B testing | Distributions, hypothesis testing, p-values, confidence intervals; walk through one A/B test example |
| **Day 6** | Visualization & case studies | Build a small dashboard; practice 2 business case questions with a structured approach (define metric → segment → hypothesize → validate) |
| **Day 7** | Mock interview & review | Timed SQL test, explain one project in 3 minutes, rehearse behavioral answers, review weak areas |

## Final Tips

- Always clarify the business question before touching the data.
- State your assumptions out loud, especially on case-study questions.
- Explain findings in plain language — lead with the insight, then the supporting numbers.
- Double-check SQL logic for duplicates and NULLs introduced by joins.
- Bring one portfolio project and be ready to explain your data source, method, and impact.
- Prepare questions about data quality, tooling, and how analytics influences decisions at the company.

---

> **Disclaimer:** All preparation plans are AI-generated summaries based on public web search results, produced for academic purposes only — not professional career advice.
