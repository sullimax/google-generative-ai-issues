# Google Generative AI Issues Research Project

This repository contains research data about open bug issues in Google's generative AI repositories on GitHub.

## Project Overview

The goal of this project was to:
1. Search for repositories owned by 'google' that have 'generative-ai' in their name
2. Count how many open issues each repository has that are labeled 'type:bug'
3. Organize this data in a CSV file for analysis

## Data Collection

The data was collected on November 30, 2025 by searching GitHub repositories and issue tracking.

## Results

The CSV file `google_generative_ai_bug_report.csv` contains the following data:

| Repository Name | Open Bug Count |
|----------------|----------------|
| generative-ai-docs | 15 |
| generative-ai-go | 8 |

## Methodology

1. Used GitHub's search API to find repositories with 'generative-ai' in the name owned by Google
2. Searched each repository for open issues with the label 'type:bug'
3. Recorded the count of such issues in a CSV file

## Purpose

This exercise demonstrates:
- Repository discovery and exploration on GitHub
- Issue tracking and label filtering
- Data organization and repository management
- Working with CSV files in GitHub repositories

## Repository Structure

- `google_generative_ai_bug_report.csv`: The main data file containing repository names and bug counts
- `README.md`: This documentation file