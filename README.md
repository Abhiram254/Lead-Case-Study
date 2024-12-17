# Lead Scoring for X Education Company

##Business Problem
X Education, an online course provider for industry professionals, aims to improve its lead conversion rate. The company receives a large volume of leads daily through various sources like its website, search engines (e.g., Google), and past referrals. Leads are generated when individuals fill out a form, watch videos, or browse courses online.

Currently, X Education faces a challenge: despite acquiring many leads, the conversion rate is low—only around 30% of leads are converted into paying customers. For example, out of 100 leads acquired, approximately 70 do not convert. This inefficiency in targeting leads costs the company both time and resources.

## Objective
To address this issue, X Education seeks to identify “Hot Leads,” i.e., leads with a higher likelihood of conversion. By focusing the sales team’s efforts on these leads, the company aims to increase its conversion rate to approximately 80%.

## Dataset Overview
The dataset provided contains 9000 records of historical leads with attributes such as:

Lead Source
Total Time Spent on Website
Total Visits
Last Activity
The target variable, ‘Converted’, indicates whether a lead was successfully converted (1) or not (0). Certain categorical variables also include irrelevant values like “Select,” which need to be treated as nulls during analysis.

## Goal
The primary goal is to build a logistic regression model that assigns a lead score (0-100) to each lead. Higher scores will indicate leads with a strong likelihood of conversion, helping the sales team prioritize their outreach effectively.
