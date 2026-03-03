# AWS-SNS-SQS-Event-Notification-System
Build an event-driven notification system using AWS SNS and SQS with real time monitoring.

## Project Overview
-- This Project demonstrate an event-driven messaging system using 
- Amazon SNS
- Amazon SQS
- Amazon CloudWatch
--SNS is used to publish messages, and SQS is used tp receive and store messages for asynchronous processing.

## Service Used 
- Amazon SNS
- Amazon SQS
- Amazon CloudWatch

## Architecture
pulisher --> SNS Topic --> SNS Queue --> Consumer
This setup ensure:
1. This message delivery
2. Asynchronous communication
3. Better scalability
4. Monitoring support

## Implementation Steps
1. Created SNS Topic
2. Created SQS Queue
3. Subscribed SQS Queue to SNS Topic
4. Published test message
5. Verified  message received in SQS
6. Monitored metrics using CloudWatch

## Monitoring 
Used CloudWatch to monitor:
- Number of message published
- Message available in queue
- Message processing metrics

## Outcome
Sucessfully build a simple and scalable AWS event notification system using SNS SQS for reliable asynchronous messaging .
