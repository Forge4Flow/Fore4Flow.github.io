---
date: 2023-08-07
title: Introducing Forge4Flow
categories:
  - general
author_staff_member: boiseitguru
---

Let's face it building a DApp isn't the most dificult thing to develop... but building a secure DApp that delivers a great user experience is a mounumental task!! Building a DApp on Flow thankfully is much simplier thanks to the Resource Oriented Programming of Cadence, and the "user first" mentally that comes with that, but current tools still limit our ability to easily create great user experiences while maintaining security best practices.

Today I want to introduce you to **Forge4Flow** a suite of open source tools _forge_ secure DApps with great user experiences on the Flow Blockchain.

## Available or Coming Soon Tools

### Forge Manager - Available Sep. 2023

Having access to great tools is one thing, being able to easily deploy and manage them something else entirely... A base Forge4Flow instance alone is 6 docker containers interacting across two isolated networks. It's our mission to ensure developers are able to spend their time building great products, not stressing that their infrastructure is deployed properly. **Forge Manager** is deployed directly from our easy to install command line tool, and it handle everything from ensuring docker is installed, ensuring SSL is configured, to updating and managing multiple instances for your different environments and applications. Forge Manager also hosts a pre-built **Admin Dashboard** giving you a central place manage everything, with the piece of mind everything was setup using security best practices.

### Auth4Flow - Available Now

FCL acount-proofs are great for starting your Authentication scheme, but even Flow's own documentation states...

> FCL `account-proof` provides functionality to prove a user is in control of a Flow address. All other aspects of authentication, authorization and session management are up to the application.

Authentication, authorization and session management are arguably the most important considerations for DApp development, but they are also the easiest to mess up, especially once we start mixing web2 and web3 technologies to improve the user experience (ie. Push notifications, API Access, etc). As it stands there is no standard solution for Identiy and Access Management of Web3 applications on Flow, until now that is...

### Alerts4Flow - Available Now

### Ecosystem SDKs

#### SwiftIPFS-Image - Available Now

#### FLOAT-Swift-SDK - In Development

#### FIND-Swift-SDK - In Development

#### NFT-Storage-SDK - In Development

## Tokens, DAO, and Governance
