# Billing

This dashboard displays cost for multiple aws account.

![Header](./0_Header.png)

# Multi datasource/aws account stats
## Last month vs Current month
![Last month vs Current month](./1_Last_month_vs_Current_month.png)

## Detailed view per account
![Detailed view 1](./2_Detailed_view_1.png)

![Detailed view 2](./3_Detailed_view_2.png)

## FAQ

References: 

- [Billing Alarm and region](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html#creating_billing_alarm_with_wizard)

Why the cloudwatch region is us-east-1 ?

> "you must set your Region to US East (N. Virginia). Billing metric data is stored in this Region and represents worldwide charges"