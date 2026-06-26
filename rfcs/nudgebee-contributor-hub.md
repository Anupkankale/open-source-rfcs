> **Status:** Proposed — submitted to (https://github.com/nudgebee/nudgebee/)](#459)  
> **Author:** Anup Kankale ([@Anupkankale](https://github.com/Anupkankale))  
> **Date:** June 2026
#  Overview

As Nudgebee continues to grow across multiple domains including Frontend, Backend, AI/ML, Kubernetes, DevOps, and Documentation there is an opportunity to further improve the contributor experience.

I would like to propose a new community-focused feature called **Make Nudgebee**.

The vision is to create a dedicated Contributor Hub (`make.nudgebee.com`) same as (https://docs.nudgebee.com/) its a SubDomain of Nudgebee that provides a structured journey for developers—from discovering the project to becoming long-term contributors.

The goal is not only to help developers make their first contribution, but also to help them become active members of the Nudgebee community.

---

# Problem Statement

As an open-source project grows, its architecture naturally becomes larger and more complex.

While experienced contributors can navigate the project easily, new contributors often face questions like:

- Where should I start?
- Which part of the project matches my skills?
- Which issue should I work on first?
- Which documentation should I read?
- Which Discord channel should I join?
- Who can guide me if I get stuck?

Although all of this information already exists, it is spread across different platforms:

- Documentation
- GitHub Issues
- Discord
- Community discussions

Finding the right path becomes difficult for someone contributing for the first time.

---

#  Proposed Solution

Create a new feature called:

# Building Nudgebee

```
                     building.nudgebee.com

                            │
                            ▼

                 Welcome Contributors

                            │
                            ▼

              Choose Your Contribution Area

 ┌────────────┬────────────┬────────────┬────────────┐
 │ Frontend   │ Backend    │ AI / ML    │ Docs       │
 └────────────┴────────────┴────────────┴────────────┘

                            │
                            ▼

                Learning Path + Resources

                            │
                            ▼

                   Good First Issues

                            │
                            ▼

                  Join Discord Community

                            │
                            ▼

                    Submit Pull Request

                            │
                            ▼

                  Release Recognition 🎉
```

This platform would provide a structured contributor experience instead of requiring contributors to search across multiple platforms.

---

# Core Features

## 1. Domain-Based Contribution

Allow contributors to choose the area that matches their skills.

Example:

```
Frontend
│
├── Setup Guide
├── UI Architecture
├── Good First Issues
├── Open Issues
└── Maintainers

Backend
│
├── Go Services
├── API
├── Integrations
└── Open Issues

AI / ML
│
├── RAG
├── Models
├── Evaluation
└── Open Issues

Documentation
│
├── Guides
├── Tutorials
├── API Docs
└── Improvements
```

---
Example: This Screen of the ticket system of Wordpress How They Filter Ticket
<img width="1466" height="767" alt="image" src="https://github.com/user-attachments/assets/dcf7a54f-af52-4555-a863-4beb4a2fa070" />

## 2. Guided Learning Paths

Instead of asking contributors to read everything, provide a structured learning path.

Example:

```
Learn

↓

Setup Project

↓

Understand Architecture

↓

Read Coding Standards

↓

Pick First Issue

↓

Open Pull Request
```

---

## 3. Smart Issue Discovery

Instead of browsing hundreds of GitHub issues, contributors can filter by:

- Skill
- Technology
- Difficulty
- Labels
- Good First Issue
- Help Wanted

Example

```
React

↓

Easy

↓

Estimated Time
2 Hours

↓

Good First Issue
```

---

## 4. Discord Integration

Automatically connect GitHub labels with Discord channels.

```
Frontend Issue

↓

#frontend-contributors

Backend Issue

↓

#backend-contributors

AI Issue

↓

#ai-contributors

Docs Issue

↓

#documentation
```

Contributors immediately know where they can ask questions and collaborate.

Example Wordpress Slack Integrated With Git so New bug Issues and Feachure And Track And There Are Different Channels Core(For Main Php Wordpress Core and Coreai For Ai and core-committers)

<img width="1402" height="858" alt="image" src="https://github.com/user-attachments/assets/e7245ea7-3925-466e-a1c6-8668c21292c9" />


---

## 5. Contributor Dashboard

Every contributor gets their own dashboard.

```
My Dashboard

✔ Assigned Issues

✔ Open PRs

✔ Merged PRs

✔ Current Release

✔ Contribution History

✔ Areas of Contribution
```

---

## 6. Community Recognition

Every release should celebrate contributors.

Example:

```
Release v1.8

⭐ First Time Contributors

⭐ Top Contributors

⭐ Documentation Heroes

⭐ AI Contributors

⭐ Community Highlights
```

Small recognition creates long-term motivation.

---

#  Benefits

## Contributors

- Easier onboarding
- Better learning experience
- Faster first contribution
- Better collaboration
- Clear contributor journey

---

## Maintainers

- Better issue organization
- Less onboarding effort
- Higher-quality contributions
- Stronger contributor retention

---

## Nudgebee

- Stronger community
- Better developer experience
- More contributors
- Higher contributor retention
- Sustainable community growth

---

# 🛣 Growth Roadmap

## Phase 1

```
✔ Contributor Landing Page

✔ Domain Navigation

✔ Good First Issues

✔ Learning Resources
```

---

## Phase 2

```
✔ Discord Integration

✔ Contributor Dashboard

✔ Guided Onboarding

✔ Release Recognition
```

---

## Phase 3

```
✔ Contributor Profiles

✔ Badges

✔ Leaderboards

✔ Monthly Community Challenges
```

---

## Phase 4

```
✔ Mentor Program

✔ Community Events

✔ Hackathons

✔ Annual Contributor Awards
```

---

#  Inspiration

This proposal is inspired by successful open-source communities like:

- WordPress
- Kubernetes
- Linux
- VS Code

One common pattern across these projects is that they invest not only in technology but also in the contributor experience.

Successful communities make it easy for contributors to:

- Learn
- Collaborate
- Contribute
- Grow
- Become long-term community members

---

#  My Journey as an Open Source Contributor

Hi everyone,

I'm **Anup**, an open-source contributor who enjoys exploring how successful open-source communities are built—not just from a technical perspective, but also from a community perspective.

Recently, I started contributing to **WordPress Core**, one of the world's largest open-source CMS platforms.

Having one of my contributions merged into an official release was an exciting milestone, but it also sparked a much bigger curiosity.

I started asking myself questions beyond writing code.

> How does a project with thousands of contributors stay organized?

> How do people from different countries collaborate?

> How are new contributors onboarded?

> Why do developers continue contributing for years?

> How do enterprises and government organizations trust an open-source CMS?

Those questions encouraged me to explore the complete open-source ecosystem behind WordPress.

I spent time learning about:

- Make WordPress
- Contributor Handbooks
- Slack Communities
- Team Meetings
- WordCamps
- Release Process
- Governance Model
- Contributor Recognition
- Community Teams

Through that journey, I realized something important.

A successful open-source project is not built only by writing great code.

It is built by creating a great contributor experience.

That experience inspired me to study other successful communities like Kubernetes, Linux, and VS Code.

Although every project has its own vision and goals, they all share one common principle:

> They make contributing simple, welcoming, and rewarding.

That is what inspired this proposal.

This idea is not about copying another project.

It is about learning from successful open-source ecosystems and adapting those ideas in a way that fits Nudgebee's vision and future growth.

I believe Nudgebee already has a strong technical foundation.

With a dedicated contributor experience, we can also build a thriving community where developers can:

```
Discover

↓

Learn

↓

Contribute

↓

Collaborate

↓

Get Recognized

↓

Become Long-Term Contributors
```

Thank you for taking the time to read this proposal.

I would love to hear feedback from the maintainers and the community, and I hope this can start a discussion about the future of contributor experience in Nudgebee.

❤️ Happy Contributing!
