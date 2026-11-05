# SOC Log Monitoring & Threat Detection Using Splunk

## Project Overview

This is a hands-on cybersecurity project focused on SOC monitoring and threat detection using Splunk Enterprise on Ubuntu Linux.

The project demonstrates how to collect authentication logs, identify failed login attempts, create monitoring dashboards, and configure alerts.

## Tools & Technologies

- Ubuntu Linux
- Splunk Enterprise
- Oracle VirtualBox
- Linux Authentication Logs
- SPL (Search Processing Language)

## Project Features

- Ubuntu authentication log collection
- Failed login detection
- Authentication failure timechart
- SOC monitoring dashboard
- Total log events monitoring
- Failed login alert configuration
- Alert testing and verification

## Detection Query

index=main sourcetype=Ubuntu_Auth_Logs "authentication failure"

## Dashboard

## The Splunk dashboard includes:

1. Authentication Failure Monitoring
2. Total Log Events

## Alert

 Alert Name: Ubuntu Failed Login Detection

 Purpose: Detects failed authentication attempts on Ubuntu using Splunk logs.

## Learning Outcomes

- Linux log monitoring
- SIEM fundamentals
- SPL search queries
- Security event analysis
- Dashboard creation
- Alert configuration and testing

## Project Report

[View / Download SOC Monitoring Project Report](SOC-Log-Monitoring-Splunk-Report.pdf)

## Author

Sachin Kumar

Hands-on Cybersecurity / SOC Lab Project
