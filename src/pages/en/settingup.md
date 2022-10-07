---
title: Getting Started
description: getting started with dashcord to get up and running with development
layout: ../../layouts/MainLayout.astro
---

## Setting up

Dashcord is like any standard [next.js](https://nextjs.org) application, and follows all the conventions and good practices

To get up and running with a local dev enviornment for dsahcord follow the below steps

**Step 1 :** [Fork](https://github.com/TakshakRamteke/dashcord/fork) the repo

> Note : while creating the fork please follow the common naming convention i.e. dashcord-[your_project_name] to keep with the consistency

**Step 2 :** [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) the newly created fork

**Step 3 :** `cd dashcord`

**Step 4 :** `yarn install`

**Step 5 :** Add the necessary enviornment variables listed in `.env.example` to the `.env` file

**Step 6 :** Run database migrations via. `yarn prisma migrate dev`

> Note : Make sure to add the correct DATABASE_URL in `.env` file

**Step 7 :** Run development server by `yarn dev`
