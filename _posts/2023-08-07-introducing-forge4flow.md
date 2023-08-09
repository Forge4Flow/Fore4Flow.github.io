---
date: 2023-08-08
title: Introducing Forge4Flow
categories:
  - general
author_staff_member: boiseitguru
---

With the release Forge4Flow-Core v.0.0.2, and the documentation being about 80-90% complete... I though it was time to introduce the Flow ecosystem to **Forge4Flow** a suite of open source tools _forge_ secure DApps with great user experiences on the Flow Blockchain.

Let's face it building a DApp isn't the most dificult thing to develop... but building a secure DApp that delivers a great user experience is a mounumental task!! Building a DApp on Flow thankfully is much simplier thanks to the Resource Oriented Programming of Cadence, and the "user first" mentally that comes with that, but current tools still limit our ability to easily create great user experiences while maintaining security best practices.

## Available and Coming Soon Tools

### Forge Manager - Available Sep. 2023

Having access to great tools is one thing, being able to easily deploy and manage them something else entirely... A base Forge4Flow instance alone is 6 docker containers interacting across two isolated networks. It's our mission to ensure developers are able to spend their time building great products, not stressing that their infrastructure is deployed properly. **Forge Manager** is deployed directly from our easy to install command line tool, and it handle everything from ensuring docker is installed, ensuring SSL is configured, to updating and managing multiple instances for your different environments and applications. Forge Manager also hosts a pre-built **Admin Dashboard** giving you a central place manage everything, with the piece of mind everything was setup using security best practices.

### Admin Dashboard - Available Shortly

The `Forge4Flow-Core` application provides powerful APIs to manage your environment, however, almost all systems need a way for humans to easily manage their users, roles, tenants, event alerts, etc. Rather than wasting time building an admin dashboard most DApps will be able to rely on our Admin Dashboard that provides access to the standard functions of Forge4Flow.

Final work is being done to make the that admin dasbhoard compatible with v0.2.0 and is expected to be released within the week.

### Auth4Flow - Available Now

FCL acount-proofs are great for starting your Authentication scheme, but even Flow's own documentation states...

> FCL `account-proof` provides functionality to prove a user is in control of a Flow address. All other aspects of authentication, authorization and session management are up to the application.

Authentication, authorization and session management are arguably the most important considerations for DApp development, but they are also the easiest to mess up, especially once we start mixing web2 and web3 technologies to improve the user experience (ie. Push notifications, API Access, etc). As it stands there is no standard solution for Identiy and Access Management of Web3 applications on Flow, until now that is...

Auth4Flow offers a simple, open-source Identity and Access Management platform that simplifies Web3 authentication. It supports various authorization schemes, including RBAC, FGAC, ReBAC, and NFT/FT/Event gated access.

### Alerts4Flow - Available Now

One of the biggest advantages of the Flow Blockchain is its ability to emmit events from within contracts, thus allowing developers to react to changes as they occur. Unfortunately tooling in this area has not been widely developed. With Alerts4Flow developers can easily set up Event Monitors to receive alerts in realtime using Websockets or Webhooks.

### Ecosystem SDKs - In Development

Lack of mobile resources is a huge factor for their being very little Web3 Mobile apps. By releases ecosystem SDKs for multiple platforms we can lower the barrier to entry for new developers. We have scoped several SDKs to target for Swift (iOS).

- SwiftIPFS-Image
- FLOAT-Swift-SDK
- FIND-Swift-SDK
- NFT-Storage-SDK

## Tokens, DAO, and Governance

It's my belief that open source tools, _paticularly those with a security focus_, should be governaned colletively by the individual contributors and end users of the application, not some corporate entity. It is my goal to establish Forge4Flow as a DAO governed by the collective will, and in that spirit I welcome everyone that contributes to or uses any of these tools to join our [Discord server](https://discord.gg/S85mDy2qxE) to share your ideas. Once a community has been established, a proposal on how to move forward will be presented to the community.

## What's Next?

Check out the docs to read more about the road to v0.1.0, and join the community [Discord server](https://discord.gg/S85mDy2qxE) to share your ideas or get support.
