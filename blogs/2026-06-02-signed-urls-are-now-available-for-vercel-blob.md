---
title: "Signed URLs are now available for Vercel Blob"
url: "https://vercel.com/changelog/signed-urls-are-now-available-for-vercel-blob"
date: "2026-06-02"
author: "Agustin Falco, Elliot Dauber"
feed_url: "https://vercel.com/blog/rss.xml"
---
Vercel Blob now supports time-bound signed URLs that enable scoped access to specific operations (get, put, head, delete) on individual objects for up to 7 days. The feature allows direct browser uploads via multipart and conditional deletes using ETags, while integrating with OIDC authentication to keep sensitive tokens server-side.
