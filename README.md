---
page_type: sample
languages:
  - javascript
products:
  - nodejs
  - azure-active-directory
  - microsoft-identity-platform
urlFragment: active-directory-javascript-nodejs-webapi-v2
description: "This sample demonstrates how to protect a Node.js Web API that is secured using Azure AD"
---

# Protect a Node.js web API with Microsoft identity platform

 1. [Overview](#overview)
 1. [Scenario](#scenario)
 1. [Contents](#contents)
 1. [Prerequisites](#prerequisites)
 1. [Setup](#setup)
 1. [Registration](#registration)
 1. [Running the sample](#running-the-sample)
 1. [Explore the sample](#explore-the-sample)
 1. [About the code](#about-the-code)
 1. [Deployment](#deployment)
 1. [More information](#more-information)
 1. [Community Help and Support](#community-help-and-support)
 1. [Contributing](#contributing)
 1. [Code of Conduct](#code-of-conduct)

## Overview

This sample demonstrates [how to protect a Node.js Web API](https://docs.microsoft.com/azure/active-directory/develop/quickstart-configure-app-expose-web-apis) with the [Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/) and [Azure Active Directory (Azure AD)](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-whatis) using the [passport-azure-ad](https://github.com/AzureAD/passport-azure-ad) library.

You will need a **client** application for calling the web API. For a web API sample that is coupled with a client app, see: [JavaScript Single-page application & Node.js web API Tutorial](https://github.com/Azure-Samples/ms-identity-javascript-tutorial/tree/main/3-Authorization-II/3-1-call-api)

Alternatively, you may modify the following samples to call this web API (this requires some familiarity, so follow the tutorial above first):

- [JavaScript Single-page Application with MSAL.js 2.x using the auth code flow with PKCE](https://github.com/Azure-Samples/ms-identity-javascript-v2).
- [Angular Single-page application with MSAL-Angular using the implicit flow](https://github.com/Azure-Samples/active-directory-javascript-singlepageapp-angular)

For best results, configure your client app in parallel with configuring this API sample.

