---
title: projects
layout: page
permalink: /projects
---

# my projects

## [wound healing tool](https://github.com/nurzhamanka/whiplugin)
For my **Senior Project** at Nazarbayev University, I decided to build a tool for performing batch image segmentation of microscope images obtained during a [wound healing assay](https://en.wikipedia.org/wiki/Wound_healing_assay). The tool is actually a plugin for [FIJI/ImageJ2](https://fiji.sc/), an open-source Java image processing program. My friend, *Sholpan Kauanova, a Ph.D. student at Nazarbayev University*, inspired me to develop this. The project is built using the tools from the [SciJava](https://scijava.org/) ecosystem.

**The plugin consists of two parts:** *the base tool* for processing a dataset or a set of datasets using a predefined algorithm with some tunable parameters, and *a GUI* allowing users to create graphs representing custom algorithms.

## [CharityFinder REST API](https://github.com/nurzhamanka/charity-api)
For my Software Engineering class, I built the back end for *CharityFinder*, a web application for finding and managing charities (mock charities). It is written using **Spring** and **Kotlin**. The back end supports CRUD operations via a RESTful API, the users are authenticated via JWT and authorized according to their roles.

### Features

-   Charity Managers can create and manage their charity organizations
-   Users can select a charity from the list and "donate" to it
-   All users have a profile with some contact information and a customizable avatar generated via  [tinygraphs](https://www.tinygraphs.com/)
-   App is built using **Spring Boot**, the data layer uses **Spring Data**
-   **Spring Security** was used for... well... security, with JWT as the authentication method

[**more on my GitHub...**](https://github.com/nurzhamanka)
