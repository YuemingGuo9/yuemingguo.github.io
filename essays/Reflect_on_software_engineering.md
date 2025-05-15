---
layout: essay
type: essay
title: "Reflect on software engineering"
# All dates must be YYYY-MM-DD format!
date: 2025-05-12
published: true
labels:
  - Engineering
---
# Reflecting on Software Engineering

As this course comes to a close, I realize that while we built web applications using technologies like React, Next.js, and PostgreSQL, what I truly gained goes far beyond web development. I now have a deeper understanding of core software engineering principles that are applicable in any software domain—not just on the web. In this reflection, I will focus on three key concepts: **Agile Project Management** (specifically *Issue Driven Project Management*), **Configuration Management**, and **Design Patterns**. Each of these has broadened how I think about building software in general.

## Agile and Issue Driven Project Management

One of the most valuable lessons from this course was learning Agile Project Management, particularly through a style called **Issue Driven Project Management (IDPM)**. 

**Agile** is a methodology that emphasizes iterative development, frequent reassessment, and close collaboration. Unlike traditional "waterfall" methods where projects are planned entirely upfront, Agile breaks projects into small, manageable iterations called *sprints*. Teams adapt to feedback and changing requirements quickly, which is essential in today’s fast-paced software environments.

**IDPM** is a specific approach to Agile where work is organized around GitHub issues. Each issue represents a unit of work: a bug, a feature, a refactor, etc. These issues are tracked on a project board and are assigned, estimated, and completed by the team during sprints. This process taught me how to turn vague goals into concrete, trackable tasks, and how to manage time effectively.

What makes IDPM powerful is that it's not tied to web applications at all. I can easily see myself using this same system to manage a mobile app project, a machine learning experiment, or even a research paper. Anything that can be broken into trackable tasks can benefit from IDPM. The real benefit is not just in checking off tasks but in building a culture of **transparency**, **accountability**, and **adaptability** within a team.

## Configuration Management

Before this course, I had a shallow understanding of **configuration management**. Now I know it’s a foundational concept in software engineering that ensures code works consistently across environments—development, testing, and production.

Configuration management includes:

- **Version control systems** like Git
- **Environment variables** stored in `.env` files
- **Dependency tracking** through package managers like `npm`
- **Database schema management** tools like Prisma

During this class, I experienced firsthand what happens when configuration is not managed properly: bugs that only appear in production, broken deployments, or mismatched database schemas. Learning how to use tools like `.env` files for secret keys, how to set up CI workflows using GitHub Actions, and how to perform safe migrations with Prisma gave me the skills to maintain software systems reliably.

Outside web apps, configuration management is just as crucial—whether I’m working on a command-line utility, a desktop app, or a serverless AI system. Any software that has multiple environments or dependencies needs this kind of discipline.

## Design Patterns

Lastly, we touched on the concept of **design patterns**, which are reusable solutions to common software design problems. Examples include:

- The **Singleton** pattern – ensuring only one instance of a class exists
- The **Observer** pattern – where objects subscribe to changes in other objects
- The **Model-View-Controller (MVC)** pattern – which helps separate concerns in application architecture

Design patterns are about *thinking at a higher level*—they are not about syntax, but structure. While React enforces certain patterns like component-based design, the true value comes from understanding *why* these structures exist. If I build a game engine or a financial analytics tool in the future, the patterns I learned here will guide me to make it **modular**, **testable**, and **maintainable**.

## Conclusion

This course has been more than just a web development class—it was a true introduction to software engineering. I now understand how Agile methods like IDPM help teams stay focused and adaptable, how configuration management keeps software predictable and secure, and how design patterns create reusable and elegant solutions. These principles will guide me whether I’m building a mobile app, writing backend services, or contributing to open-source projects. I feel more confident stepping into future projects knowing I’m not just writing code—I’m engineering software.
