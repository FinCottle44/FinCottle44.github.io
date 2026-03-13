---
layout: project
title: SendItDirect API Deployment
date: 2026-03-13
image: https://www.senditdirect.co.uk/assets/branded-van-containers-BFViWLZB.jpg
description: Fast delivery quoting and booking system API
---

## Overview

Developed a scalable REST API for [SendItDirect](https://senditdirect.co.uk), a fast delivery service provider. The API enables real-time delivery quoting and booking functionality, allowing customers to quickly access pricing and reserve delivery slots.

## Challenge

SendItDirect needed a robust backend system to handle high-volume delivery quote requests and bookings with minimal latency. The existing system couldn't scale to meet peak demand periods.

## Solution

Built a production-grade serverless API on AWS with:

- **Serverless Architecture**: API Gateway with Lambda functions for automatic scaling and cost efficiency
- **Real-time Quoting Engine**: Optimized algorithms for instant delivery cost calculations based on distance, weight, and service level
- **Booking System**: Reliable transaction handling with DynamoDB for consistency and performance
- **API Security**: JWT authentication and rate limiting via API Gateway to protect endpoints
- **Monitoring & Logging**: CloudWatch integration for performance tracking and debugging
- **Database**: RDS for transactional data with DynamoDB for high-throughput operations

## Results

The client is extremely satisfied with the deployment. The API now handles thousands of quote requests daily with sub-second response times, enabling a seamless customer experience for their delivery booking platform.

## Technologies

- AWS (API Gateway, Lambda, RDS, DynamoDB, CloudWatch)
- RESTful API Design
- Serverless Architecture
- Database Optimization
- Cloud Infrastructure
