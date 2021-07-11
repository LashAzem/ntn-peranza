---
createdAt: 2021-07-11T23:19:44.721Z
title: Esto es una prueba de Contenido
description: Esto es un texto descriptivo.
---
Back in your Netlify dashboard:

1. Go to **Settings > Identity**, and select **Enable Identity service**.
2. Once enabled, select **Settings and usage**, and scroll down to **Registration preferences**. You can set this to either **Open** or **Invite only**, but usually **Invite only** is your best bet for a personal site.
3. If you don't want to create an account, or would like to use an external provider such as GitHub or Google, you can enable those services under **External providers**.
4. Scroll down to **Services** and click **Enable Git Gateway**.

**Accessing the CMS** Once you've reached this point, you should be able to access the CMS in your browser at `http://localhost:3000/admin`. You'll be prompted to add the URL of your Netlify site. Once you've added that URL, you can log in with an Identity account or with one of the External Providers you enabled in step 3 above. For the sake of this tutorial, you can create a blog post in the CMS, and publish it! Once you `git pull` in your project, the blog post will show up in the project at `content/blog/<slugified-blog-post-title>.md`.