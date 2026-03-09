# AWS CloudWatch Monitoring Setup

This project demonstrates how to monitor AWS infrastructure using Amazon CloudWatch.

## Services Used

- Amazon CloudWatch
- AWS EC2
- CloudWatch Logs
- CloudWatch Alarms

## Monitoring Setup

1. Enabled CloudWatch monitoring for EC2 instances
2. Created CloudWatch alarms for CPU utilization
3. Configured log monitoring
4. Set alert notifications for critical metrics

## Example Alarm Configuration

Metric: CPUUtilization  
Threshold: 80%  
Evaluation Period: 5 minutes

If CPU usage exceeds 80%, CloudWatch triggers an alert.

## Key Benefits

- Real-time monitoring of infrastructure
- Automated alert notifications
- Faster incident response
- Improved system reliability
