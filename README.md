# matplotlib-challenge

This is an assignment for the University of Minnesota Data Analytics and Visualization Boot Camp.

# Pymaceuticals, Inc.

## Analysis Summary
- There is a positive correlation between mouse weight and the average tumor size. This would indicate that the healthier the mouse's weight is, the smaller their tumors are likely to be.
- Capomulin is an effective treatment for tumors in mice, though the effects are slow.
- Capomulin and Ramicane are more effective at treating these tumors than Infubinol and Ceftamin, based on the study observed here.

## Background

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## Analysis

In this study, 249 mice were identified with tumors. However, one mouse was found to have a duplicate ID, so the data was removed, making 248 mice. There was an equal distribution of sex (51% male and 49% female), and a fairly even distribution between all of the drug regimen groups (including the Placebo group). Timepoints were taken at intervals of 5 days (0, 5, 10, 15, 20, 25, 30, 35, 40, 45). 

This study shows a correlation between mouse weight and average tumor volume (0.84, which is considered a strong correlation). This indicates that the healthier the mouse's weight, the smaller the tumor volume should be. Keeping the mice on healthier diets may help to reduce tumor volume in these mice.

Capomulin performed similarly to Ramicane and better overall than either Infubinol or Ceftamin. Capomulin did show a decrease in tumor volume after 45 days. It is a slow decrease, but a decrease nonetheless. Many of the drug regimens showed a high variance, meaning it is beneficial to narrow the comparison down to four regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Comparing these four regimens, Capomulin and Ramicane perform better overall than Infubinol and Ceftamin.