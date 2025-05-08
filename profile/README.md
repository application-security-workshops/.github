# Application security workshop

A two day security workshop for developers and architects.

## Day 1: Application security workshop

- 08:30 - 12:00
  - Introduction, goals of the workshop
  - Application security overview
  - OpenID Connect, OAUTH flows
- lunch
- 13:15 - 18:00
  - DevOps security
  - Protecting the session, client
  - API authorization
  - Securing SPA applications

## Day 2: Architecture security workshop

- 08:30 - 12:00
  - Introduction, goals of the workshop
  - Application architecture security overview
  - OpenID Connect, OAUTH flows (Recap)
  - App security architectures
- lunch
- 13:15 - 18:00
  - Choose the correct identity provider, authentication platform
  - DevOps security advanced
  - API Authorization advanced
  - Authorization architecture

# Day 1: Application security workshop

This workshop shows how authentication, authorization and security requirements can be implemented using ASP.NET Core and Azure DevOps with different identity providers. Some of the different approaches when implementing these in SPAs, or ASP.NET Core Razor/MVC will be explained as well as the different OpenID Connect/OAuth flows which should be used or can be used for these types of solutions.

## Workshop requirements

- PC with .NET Core 9 SDK and Visual Studio 2022 or Visual Studio Code installed
- NodeJS LTS version 18/20/22
- Internet WLAN connection (Guest WiFi provided by isolutions)
- GitHub account

## Introduction, goals of the workshop

Introduction to the workshop, explain some of the aims and targets of the day and what expectations the attendees have or should have.

## Application security overview

The module gives an overview of application security architecture and explains some of the topics from a top-level perspective. The different areas of applications security will be explained as well as best practice for multi factor authentication.

## OpenID Connect, OAUTH flows

This module explains the best practices for implementing OAuth and OpenID Connect in a software. The recommended flows and how they work will be highlighted and the attendees show gain a clear knowledge of when to use which flow for which application type.

## DevOps security

In the DevOps Security part, the focus is on possible attack vectors in the development process and how these can be mitigated in general and detected in relation to the source code using static security testing.

## Protecting the session, client

Learn how your session can be attacked even if your authentication flow is perfect. Team up with your browser and learn about important security headers. In the exercises, you will demonstrate multiple attacks on an application and learn how to mitigate them.

## API authorization

This module looks at implementing authorization for APIs, exploring the different ways to secure the APIs, for example cookies, self contained access tokens or reference tokens and introspection.

## Securing SPA applications

Securing single page applications is hard. This is no common recommended best practice for securing SPA applications. This module shows the current recommendations for implementing security in SPAs and things like the backend for frontend architecture (BFF) will be explained.

# Day 2: Architecture security workshop

This workshop shows how security architecture requirements can be planned and designed using ASP.NET Core and Azure DevOps with different identity providers. Some of the different approaches when designing these in cloud solutions, high security architectures will be explained as well as the different OpenID Connect/OAuth flows which should be used or can be used for these types of solutions.

## Workshop requirements

- PC with .NET Core 9 SDK and Visual Studio 2022/Visual Studio Code installed
- NodeJS LTS version 20
- Internet WLAN connection
- GitHub account
- Personal Azure tenant (create, if not yet done under https://my.visualstudio.com/ by clicking `Activate` on `Azure - $150 monthly credit`)

## Introduction, goals of the workshop

Introduction to the workshop, explain some of the aims and targets of the day and what expectations the attendees have or should have.

## App Architecture security Overview

The module gives an overview of application security architecture and explains some of the topics from a top-level perspective. Things like development security, infrastructure security, governance will be explained and well as how to plan and define requirements for security.

## OpenID Connect, OAUTH flows (Recap)

This module is a recap of the application security module and explains the best practices for OAuth and OpenID Connect. The recommended flows and how they work will be highlighted and the attendees show gain a clear knowledge of when to use which flow for which application type.

## App Security architecture

This module explores architecture requirements for application security. The module makes use of application architecture best practices like for example quality attributes and explains what makes a good security context diagram, what type of requirements should be visible in a good diagram.

## Choose the correct identity provider, authentication platform

Choosing the right identity provider for your software solution is not easy. This module explains some of the advantages and disadvantages of the different identity provider products and should give you the knowledge to choose the right identity provider for your solution authentication and authorization.

## DevOps security advanced

This module provides an overview of GitHub features with a focus on security features and goes into detail in the context of DevOps security. In particular, in the area of GitHub actions.

## API authorization advanced

This module looks at implementing authorization for APIs, exploring things like delegated user definitions or application access tokens, Other topics like implementing and using the on behalf of flow and using Azure continuous access in your applications are explained as well as general or advanced API security topics.

## Authorization architecture

This module starts by explaining the technical implementation of current best practice when implementing authorization in ASP.NET Core applications. The module then looks at designing and planning application authorization architecture in software solutions.
