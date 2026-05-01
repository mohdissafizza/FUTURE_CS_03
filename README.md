# API Security Risk Analysis

## Project Overview
This project presents a security analysis of a public API to identify common vulnerabilities and assess potential risks in modern SaaS environments. The analysis follows a read-only and ethical approach.

## Objective
Analyze API endpoints  
Identify security risks  
Assess authentication and authorization mechanisms  
Evaluate data exposure in API responses  
Provide remediation recommendations  

## Scope
Public API testing (JSONPlaceholder)  
Read-only requests (GET)  
No exploitation or harmful activity  
Educational and security analysis purposes only  

## Tools Used
Postman  
Browser Developer Tools  
API Documentation  

## API Tested
https://jsonplaceholder.typicode.com/

## Methodology
Reviewed API documentation  
Tested endpoints using Postman  
Inspected response data and headers  
Identified potential security risks  
Classified risks based on severity  
Provided mitigation strategies  

## Identified Risks
No Authentication (High)  
No Authorization (High)  
Excessive Data Exposure (Medium)  
No Rate Limiting (Medium)  
Missing Security Headers (Low)  

## Risk Summary
No Authentication is a High severity risk  
No Authorization is a High severity risk  
Excessive Data Exposure is a Medium severity risk  
No Rate Limiting is a Medium severity risk  
Missing Security Headers is a Low severity risk  

## Recommendations
Implement authentication mechanisms (JWT or API keys)  
Enforce authorization using role-based access control (RBAC)  
Limit data exposure in API responses  
Apply rate limiting to control request frequency  
Add appropriate security headers  

## Ethical Considerations
This analysis was conducted using publicly available APIs and followed ethical guidelines. No exploitation or harmful testing was performed.

## Author
Mohdissa Fizza
