# AWS CloudWatch + EC2 Monitoring Dashboard
# Uses CloudWatch to monitor system metrics like CPU usage, create an alarm, and configure email alerts using SNS (Simple Notification Service).


## Overview
This project demonstrates how to monitor an EC2 instance using Amazon CloudWatch, create alarms for high CPU utilization, and send alert notifications using SNS.

## Tools Used
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS

## Steps
1. Launch an EC2 instance (t2.micro)
2. Install stress tool
3. Create CloudWatch alarm (>70% CPU for 5 mins)
4. Configure SNS for email alerts
5. Create CloudWatch dashboard for visualization
6. Trigger alarm using stress command
7. Receive alert email notification


