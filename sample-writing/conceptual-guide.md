---
title: Authentication vs. Authorization: Security concepts for non-security teams
summary: This guide introduces non-technical people to the concept of authorization and authentication.
---

## Authentication vs. Authorization: Security concepts for non-security teams

If, like me, you’ve never quite made a distinction between authorization and authentication, this conceptual guide is for you. This guide explains authentication and authorization, provides an example, and compares them in a way that you will not forget.

Both Authorization and Authentication are distinct processes in an organization's identity and access management systems. 

Think of it this way: gaining access to any resource requires passing two checkpoints—first, proving your identity (authentication), and then proving you have permission to be there (authorization).

### Authentication

Authentication is proving yourself. It asks, “Who are you?”. Authentication relies on credentials such as passwords, facial scans, security tokens, one-time passwords (OTP), and fingerprints to verify your identity.

Authentication requires a key to grant you access. 


### Authorization

Authorization is the process of requesting access to specific resources or privileges. Authorization states, “This is what you are allowed to do.” Authorization is based on user permissions, which outline the actions you can perform. It says, “Yes, you are who you say you are, but I need to know how much access you get.”

Authorization gives you access based on set permissions. 

![Diagram showing how Authentication and Authorization works](/diagrams/auth-flow.png)

### The hotel key card analogy

Consider authentication and authorization in the context of a hotel key card.

Authentication: You check in at the front desk and prove you're the person who made the reservation (ID + confirmation number). You're given a key card.

Authorization: Your key card only opens certain doors - your room, the gym, and the lobby, but not the penthouse suite, staff areas, or other guests' rooms. The card identifies you and determines what you're authorized to access.

### Authentication vs. Authorization

Below is an overview of the key differences between authentication and authorization.

| S/N  | Characteristics | Authentication | Authorization |
| ---- | --------------- | -------------- | ------------- |
| 1 | Core question | Who are you? | What can you do? |
| 2 | Example | Entering a password to log into Gmail | Accessing the admin panel vs. reading emails |
| 3 | Purpose | Verifies identity | Determines permission |
| 4 | Occurence | At login | Every time you try to access something |
| 5 | What it checks | Credentials (tokens, passwords, biometrics) | Roles, permissions, and access levels. |
| 6 | Process type | One-time verification | Continous checks |
| 7 | Result | Binary (authenticated or not) | Granular (several permission levels) |
| 8 | Failure message | “Invalid login” or “access denied” | “You do not have permission” or “forbidden” |
| 9 | Technical focus | Identity verification | Access control |
| 10 | Changeability | Static (Your identity) | Dynamic (permissions can change) |
| 11 | Data required | User credentials | User roles and permissions |
| 12 | Dependencies | Independent process | Depends on authentication |


Key relationship: You cannot have authorization without authentication. Authentication is the prerequisite for authorization. You need to prove your identity before the system determines what you can access.

### Importance of Authentication and Authorization

Authentication and authorization aren't just technical buzzwords - they directly impact everyone's ability within a business or organization to do their job safely and effectively. They’re the invisible systems that keep customers and businesses safe.

Here's why authentication and authorization are critically important:

#### Makes Work Easier

Sound auth systems give people access to exactly what they need for their job - no more, no less. This reduces confusion, support tickets, and time wasted trying to access unnecessary resources.

#### Builds Customer Trust

When customers know strong security measures protect their data, they're more likely to do business with you. Data breaches destroy trust and can take years to rebuild.

#### Protects What Matters Most

These systems safeguard sensitive information, including customer data, financial records, and business secrets. Without them, anyone could access anything, putting both the company and customers at risk.

## What this means for you 
Next time you encounter an access issue or need to discuss user permissions, you'll know the right questions to ask. Is this an authentication problem (can't prove identity) or an authorization problem (identity confirmed but lacking permission)? 

This simple distinction will save you time and help you communicate more effectively with your technical colleagues.

Introduction
definition
diagram
background
use cases
comparison
related resources


Keep in mind:

Make connection to other things.
Provide background and context - design decisions, historical reasons, example, and anything that gives the person an idea of why this matters.
Share Opinion and perspective
It is about a topic