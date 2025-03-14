---
type: ProjectLayout
title: User Experience Monitoring (UEM)
colors: colors-a
date: '2022-01-22'
client: Air Force
description: >-
  Web analytics software that tracks users within a DoD environment. Supporting
  numerous websites and mobile applications within the Air Force.  
featuredImage:
  type: ImageBlock
  url: /images/UEM Logo_Color_onDark.png
  altText: UEM Logo
media:
  type: ImageBlock
  url: /images/bg3.jpg
  altText: Project image
---
User Experience Monitoring (UEM) is an enterprise application monitoring suite designed to track, monitor, and report application and user data, focusing on quantitative and qualitative metrics. It currently uses Matomo as its site analytics tool to capture user activity within a website, generating aggregate reports on visit histories, performance metrics, and system configurations. This data collection is facilitated by a JavaScript code snippet that is integrated into the application's web pages, usually just after the opening \`<body>\` tag. Once live, this snippet collects data every time a user visits the app and sends it to Matomo's HTTP tracking API, including details like visit time, page being visited, and browser information, which is then securely stored on Cloud One.


UEM consists of three main components: Matomo, OpenSearch, and Keycloak. Matomo captures user activity and creates analytics reports, OpenSearch provides a reporting interface for viewing data from Matomo, and Keycloak manages access to both Matomo and OpenSearch, requiring users to log in via CAC. The UEM Team adheres to stringent security standards, hosting the service in a Cloud One IL4 environment, undergoing security hardening, and scanning new production code using the accredited BESPIN IL-5 Mission Delivery as a Service (MDaaS) pipeline.


For development teams, integrating UEM involves adding a provided JavaScript code snippet to the application's pages, which can be done globally based on the app's architecture. Once deployed, the snippet collects data and sends it to Matomo. Support is available from the UEM team via email at support.uem\@teambespin.us for assistance with setup and further details. The UEM service ensures secure data storage and provides resources to understand its impact on site performance and how Matomo functions.
