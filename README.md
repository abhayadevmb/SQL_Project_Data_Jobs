# Data Analyst Job Market Analysis

A comprehensive SQL-based project analyzing the data analyst job market to identify salary trends, in-demand skills, and optimal career paths for aspiring analysts.

## Introduction

This project investigates the remote data analyst job market to answer key career development questions: What are the highest-paying positions? Which skills command the best salaries? What skills are most frequently requested by employers? By combining data from over 100,000 job postings with company information and skill requirements, I've created a data-driven guide to navigating the competitive data analyst landscape.

## Background

The data analyst role has become increasingly competitive, with salaries and skill requirements varying significantly across the market. This project emerged from the need to objectively analyze which skills deliver the best return on investment for career development. Rather than relying on assumptions, I gathered and analyzed real job market data to identify patterns and trends. The dataset includes job postings from 2023, featuring remote positions posted across major tech companies and consulting firms. By examining the intersection of salary, demand, and required skills, this analysis reveals actionable insights for both job seekers and career planners.

## Tools I Used

- **SQL (Advanced Querying)**: Built complex queries using CTEs, JOINs, and aggregation functions to extract and analyze job market data
- **Database Design**: Structured data across multiple normalized tables (job_postings_fact, company_dim, skills_dim, skills_job_dim) for efficient querying
- **Data Analysis & Visualization**: Analyzed patterns across salary distributions, skill demand, and market trends

## The Analysis

This project explores five key questions about the data analyst job market:

### 1. **Top-Paying Data Analyst Jobs**

Identified the 10 highest-paying remote data analyst positions, examining salary ranges, hiring companies, and market leaders. This query filters for positions with documented salaries to provide realistic compensation expectations.

### 2. **Skills Required for High-Paying Roles**

Analyzed what skills command the highest salaries. By joining job postings with their associated skill requirements, I mapped the technical and soft skills that appear most frequently in top-paying positions.

### 3. **Most In-Demand Skills**

Determined which skills employers request most often, providing insight into market priorities and hiring trends. This helps job seekers identify skills that increase employability regardless of salary.

### 4. **Top Paying Skills by Average Salary**

Ranked the top 25 skills by average salary to understand which technical competencies translate to better compensation packages.

### 5. **Optimal Skills to Learn**

Combined demand and salary metrics to identify skills that offer the best balance of job availability and earning potential. This analysis focuses on remote positions and filters for skills requested in at least 10+ job postings to ensure statistical relevance.

## What I Learned

- **High demand doesn't always mean high pay**: Some frequently requested skills (like Excel) don't necessarily lead to top salaries, while specialized skills command significant premiums
- **Remote work remains competitive**: The remote job market for data analysts is robust, with substantial salary ranges depending on skill composition and company size
- **Niche skills create value**: Less common technical skills tend to have higher average salaries, suggesting premium compensation for specialized expertise
- **SQL dominance**: SQL appears consistently across all skill requirement levels, reinforcing its status as the foundational skill for data roles
- **Market consolidation**: A relatively small number of large tech and consulting companies dominate top-paying remote positions

## Conclusions

This analysis provides a clear roadmap for data analyst career development. Rather than chasing every trending skill, job seekers should focus on building a strategic mix of high-demand core skills (SQL, Python, Excel) while developing 1-2 specialized skills that align with their interests. The data reveals that remote data analyst positions offer competitive compensation, particularly for those who can demonstrate expertise in advanced analytics, visualization tools, and cloud platforms. The job market rewards continuous learning and skill diversification, but also values demonstrated competency in foundational tools that remain consistently in demand.
