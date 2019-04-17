## Day 4

In day 4 we covered Cloudwatch. Cloudwatch is monitoring and loggin service on AWS. We launched an application using an autoscaling group , sent some dummy requests to it and generated events and visualized it on a dashboard.

- Cloudwatch Metrics lets you monitor the metrics of infrastructure like CPU Utlization, Network in/out etc
- Cloudwatch logs let you gather and store Application logs like Apahce webserver access logs 
- Cloudwatch Alarm let you create alarms for metrics , then you can alert using SNS
- Cloudwatch Event let you perform an action on a schedule ( Like a CRON server) 
- Cloudwatch dashboard lets you visualize your metrics to monitor things at a glance


> # What is Amazon CloudWatch?
Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time. You can use CloudWatch to collect and track metrics, which are variables you can measure for your resources and applications.

The CloudWatch home page automatically displays metrics about every AWS service you use. You can additionally create custom dashboards to display metrics about your custom applications, and display custom collections of metrics that you choose.

You can create alarms which watch metrics and send notifications or automatically make changes to the resources you are monitoring when a threshold is breached. For example, you can monitor the CPU usage and disk reads and writes of your Amazon EC2 instances and then use this data to determine whether you should launch additional instances to handle increased load. You can also use this data to stop under-used instances to save money.

With CloudWatch, you gain system-wide visibility into resource utilization, application performance, and operational health.





## Reference
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html

