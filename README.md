# IAM-workshop-01-Okta-SSO-SAML
Hands on IAM lab demonstrating user provisioning, group management, SAML based SSO, and application access management using Okta and Salesforce.


IAM Workshop #1: Introduction to Identity & Access Management

Overview

This project documents my completion of the IAM Workshop #1: Introduction to Identity & Access Management. The workshop provided a hands-on introduction to core IAM concepts and demonstrated how organizations manage user identities, authentication, authorization, and application access using Okta and Salesforce.

Objectives

The goals of this lab were to:

* Understand Identity and Access Management (IAM)
* Learn the difference between Identity, Authentication, and Authorization
* Create and manage users in Okta
* Create and manage groups in Okta
* Configure Single Sign-On (SSO) using SAML
* Assign applications to groups
* Test and troubleshoot authentication issues
* Review system logs for auditing and troubleshooting

Technologies Used

* Okta
* Salesforce
* SAML 2.0
* Single Sign-On (SSO)
* Multi-Application Access Management

IAM Concepts Learned

Identity

An identity represents a user within an organization and contains attributes such as username, email address, department, and job role.

Authentication

Authentication verifies who a user is through credentials such as passwords, MFA, or biometric factors.

Authorization

Authorization determines what resources a user can access after successfully authenticating.

Single Sign-On (SSO)

SSO allows users to authenticate once and access multiple applications without repeatedly entering credentials.

Security Assertion Markup Language (SAML)

SAML is a federation protocol used to exchange authentication and authorization data between an Identity Provider (IdP) and a Service Provider (SP).

Lab Activities

1. User Creation

Created users within Okta to simulate an enterprise environment.

Example Users:

* John Smith
* Sarah Davis
* Mike Wilson

2. Group Creation

Created groups to organize users by job function.

Examples:

* HR
* Finance
* IT
* Sales

3. Salesforce SSO Configuration

Configured Salesforce as a Service Provider and Okta as the Identity Provider.

Tasks Completed:

* Created SAML application
* Configured SAML settings
* Established trust relationship
* Tested authentication flow

4. Application Assignment

Assigned Salesforce access through group membership.

Benefits:

* Simplified administration
* Reduced manual provisioning
* Improved access control

5. Authentication Testing

Validated:

* User login
* Group-based access
* SAML authentication
* Access permissions

6. Troubleshooting and Log Analysis

Reviewed Okta logs to identify:

* Failed login attempts
* SAML errors
* Authentication events
* User activity

## Architecture Diagram

## Architecture Diagram

![IAM Architecture](PASTE_THE_GITHUB_IMAGE_URL_HERE)

Skills Demonstrated

* Identity and Access Management (IAM)
* User Provisioning
* Group Management
* Role-Based Access Control (RBAC)
* Single Sign-On (SSO)
* SAML Federation
* Access Management
* Authentication Troubleshooting
* Security Log Analysis
* Identity Governance Fundamentals

Key Takeaways

This workshop helped me understand how IAM systems operate in real-world environments. I gained hands-on experience with identity lifecycle management, access control, SSO implementation, and authentication troubleshooting using industry-standard tools.

The lab reinforced the importance of ensuring that the right users have the right access to the right resources at the right time while maintaining security and compliance.

Future Improvements

* Integrate Active Directory with Okta
* Implement Multi-Factor Authentication (MFA)
* Explore SCIM provisioning
* Configure Role-Based Access Control (RBAC)
* Build automated Joiner-Mover-Leaver workflows
* Implement Identity Governance processes