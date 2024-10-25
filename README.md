# Customer Churn Detection Project

## Introduction
Customer churn, where customers discontinue using a company’s products or services, is a critical challenge for businesses. This project aims to develop a machine learning solution to predict churn, allowing businesses to take proactive actions to retain customers. Retaining existing customers is significantly more cost-effective than acquiring new ones, making churn prediction an essential tool for business sustainability.

## Objectives
- Build an accurate machine learning model to predict customer churn.
- Identify key factors contributing to churn.
- Develop a deployable solution capable of real-time churn prediction.
- Enable targeted retention strategies informed by predictive insights.
- Reduce customer acquisition costs by enhancing retention rates.

## Problem Statement

### Business Challenge
Organizations, especially those with subscription models or repeat customers, face financial losses when customers leave. Without a systematic churn prediction approach:
- Companies may not identify at-risk customers before they leave.
- Marketing resources are less effectively allocated.
- Monthly recurring revenue (MRR) becomes unpredictable.
- Customer acquisition costs increase due to higher churn.

### Technical Challenge
The churn prediction model must:
- Analyze historical customer data to detect churn patterns.
- Handle class imbalance typical in churn datasets.
- Leverage multiple customer attributes for accurate predictions.
- Be deployable in a production environment for real-time usage.

## Results and Findings

### Model Performance
- The **Random Forest classifier** achieved the best performance among tested algorithms, with high test accuracy and F1 score, demonstrating strong predictive power.

### Key Predictive Features
Top factors influencing churn:
- Customer Tenure
- Cashback Amount
- City Tier
- Warehouse-to-Home Distance
- Changes in Order Amount
- Days Since Last Order
- Satisfaction Score
- Number of Registered Addresses
- Device Registration Count
- Customer Complaints

### Customer Behavior Insights
- **Retention Rate**: 83.2% retained, 16.8% churned.
- **Platform Preference**: Mobile is the primary login method.
- **Average App Usage**: Typically 2-4 hours.
- **Device Usage**: Most customers use 3-4 devices.
- **Payment Preference**: Higher use of debit/credit cards.
- **Engagement Trend**: Drops after the second order.

## Implementation Impact
The deployed model provides:
- Real-time churn risk assessment.
- Optimized, targeted marketing campaigns.
- Improved resource allocation for retention efforts.
- Data-driven insights for customer engagement.

These insights support effective customer retention strategies, enhancing overall business sustainability.

---

This project represents a complete solution for customer churn prediction and retention strategy development.
