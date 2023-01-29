## Active projects I'm working on

### [gandi-live-dns ![GitHub Repo stars](https://img.shields.io/github/stars/SeriousBug/gandi-live-dns-rust) ![Docker Pulls](https://img.shields.io/docker/pulls/seriousbug/gandi-live-dns-rust)](https://github.com/SeriousBug/gandi-live-dns-rust)

A dynamic DNS system that works with Gandi's live DNS feature. Allows you to
host servers without a static IP address by updating DNS records whenever your
IP changes. Flexible deployments through Docker or system packages with systemd
timers.

### [Cuttlestore ![GitHub Repo stars](https://img.shields.io/github/stars/SeriousBug/cuttlestore) ![Crates.io](https://img.shields.io/crates/d/cuttlestore)](https://github.com/SeriousBug/cuttlestore)

A generic key-value storage library for Rust. Cuttlestore allows you to write
your code once and run it on many key-value stores. Right now it comes with
support for Redis and Sqlite, with planned support for CouchDB and DynamoDB.

### [Rust Embed for Web ![GitHub Repo stars](https://img.shields.io/github/stars/SeriousBug/rust-embed-for-web) ![Crates.io](https://img.shields.io/crates/d/rust-embed-for-web)](https://github.com/SeriousBug/rust-embed-for-web)

Embed files into your Rust executable. You can embed HTML, CSS, JavaScript
files, all your assets into your server to bundle them together. This simplifies
updates as your assets are always guaranteed to update together with your server.

This started as a fork of an existing project, but became a significant rewrite
of it. It includes many features useful for web servers like precomputed header
values and precompressed file contents.

### [Rust Embed Responder for Actix Web ![GitHub Repo stars](https://img.shields.io/github/stars/SeriousBug/actix-web-rust-embed-responder) ![Crates.io](https://img.shields.io/crates/d/actix-web-rust-embed-responder)](https://github.com/SeriousBug/actix-web-rust-embed-responder)

A sibling project to Rust Embed for Web, this is a responder for Actix Web that
efficiently serves your embedded files. It handles cache validation and content
type negotiation, and is built for high performance.

### [Bulgur Cloud ![GitHub Repo stars](https://img.shields.io/github/stars/bulgur-cloud/bulgur-cloud) ![Docker Pulls](https://img.shields.io/docker/pulls/seriousbug/bulgur-cloud)](https://github.com/bulgur-cloud/bulgur-cloud)

![](https://bgenc.net/img/bulgur-cloud-2022-12-30.png)

An easy to self host cloud file storage and sharing system. It's similar to Google Drive or NextCloud, but effortless to set up and maintain. Built in Rust and TypeScript, using Actix-Web and React Native.

### [live limit ![GitHub Repo stars](https://img.shields.io/github/stars/SeriousBug/live-limit) ![npm](https://img.shields.io/npm/dt/live-limit)](https://github.com/SeriousBug/live-limit)

A TypeScript library that can limit the number of concurrent async operations
running at a time. This is useful for making concurrent requests to a server
without overloading your connection. Works with promises, has no dependencies,
and comes under 1kb minzipped.

### [Query Method Middleware for Actix Web ![GitHub Repo stars](https://img.shields.io/github/stars/SeriousBug/actix-web-query-method-middleware) ![Crates.io](https://img.shields.io/crates/d/actix-web-query-method-middleware)](https://github.com/SeriousBug/actix-web-query-method-middleware)

Actix Web middleware that allows you to submit HTML forms using methods other
than `POST`. Forms normally can only be submitted through `GET` or `POST`
methods, but this middleware reroutes requests using a query parameter to other
methods.

---

## About me

- I'm currently working at [Tailwind](https://www.tailwindapp.com/) as a
  Software Engineer. I build serverless microservices with AWS CDK, Lambda, and
  DynamoDB. I also build features in our Next.js app, and help maintain our PHP
  server.
- On my free time, I love playing with [Rust](https://www.rust-lang.org/) and
  [TypeScript](https://www.typescriptlang.org/) to build open source projects.
  All the big ones are listed above! These projects usually involve React, React
  Native, Actix Web, and Docker.
- I'm learning [Svelte](https://svelte.dev/). It's very fun because it compiles
  down to simple javascript, and gracefully supports progressive enhancement.
- When I'm not programming, I am usually cooking (vegan), playing (World of
  Warcraft, Rimworld, Ultrakill), riding my bicycle, or playing with my dogs.
- I graduated from The Ohio State University with an MS in Computer Science. You can find [my publications](https://scholar.google.com/citations?user=tHrUCC4AAAAJ&hl=en&oi=ao) online.
- Pronouns: He/him

You can find me at:

- My website: [bgenc.net](https://bgenc.net)
- Mastodon: [@kaan@fosstodon.org](https://fosstodon.org/web/@kaan)

Also, here is my [gpg
key](https://keys.openpgp.org/vks/v1/by-fingerprint/F5DEC5268AA501F35FBD5978B2E280771CD62FCF).
I have never, ever, gotten an encrypted email. Send me one!
