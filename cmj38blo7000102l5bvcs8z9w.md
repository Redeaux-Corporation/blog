---
title: "Entropy CMS"
datePublished: 2025-12-12T18:57:31.255Z
cuid: cmj38blo7000102l5bvcs8z9w
slug: entropy-cms
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1765566859712/f029fb2f-a514-44c9-9624-2b060fd0da82.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1765566476569/2caf6e2e-1782-436f-b1d2-d42daf3d82ab.jpeg
tags: cloudflare, blog, nodejs, cms, typescript, cms-development, htmx, daisyui, qwik, cloudflare-r2, cloudflare-worker, cloudflare-pages, cloudflare-d1, cms-web-development, qwik-city

---

# Intro

Since I could remember if you needed a CMS for your website/webapp PHP was the simplest option, we have Wordpress, Drupal, Joomla, etc. which best case scenario it doesn't get hacked, and the pages load within 5 seconds. Though “ajax" makes seem a little bit better, it is still clunky, bloated, and insecure.

We wanted a fast and secure CMS where things load in milliseconds.

# The Stack

1. TypeScript (latest) - We create typesafe definitions for a modular system which makes it “sort of immutable".
    
2. NodeJS (latest) - TypeScript is compile into JS for Cloudflare Workers/Pages.
    
3. Wrangler (latest) - For using Cloudflare Workers/Pages/D1/R2/Durable Objects.
    
4. Vite (latest) - For theming html, tailwindcss.
    
5. Qwik (latest) - Makes the frontend on CF Pages blazing fast with resumability!
    
6. HTMX (latest) - Adds dynamic elements with Qwik’s resumability
    
7. TailwindCSS (latest) - CSS library
    
8. DaisyUI (latest) - Frontend UI components Framework.
    
9. PrelineUI (latest) - Additional frontend UI library.
    
10. EAMSA 512 TypeScript - Provides 512-bit encryption utilizing SHA3-512 hashing to secure admin section, and comment/rating system.
    
11. Modules - admin dashboard, keyfile authentication 512-bit, EAMSA 512 TS helper, Google Oauth 3 level nesting comment/rating system+Cloudflare Turnstile with moderation, ARIA-Compliance, SEO, AI search engine using ReadyIQ, D1 helper, R2 helper, DO helper, DynamicNavBar 2 level nesting, RateLimit, Blog System, Page Editor, multilingual, MD renderer, WASM, and more coming soon.
    

# In Production

We are building all of our websites/webapps/mobile apps using EntropyCMS.

EntropyCMS is a powerful system with extendability by creating custom modules.

What are we building with EntropyCMS?

1. Websites/Webapps (redeaux/moltenchain/mothership/mnft/qyra/readyiq/011/explode media group).
    
2. Blogs (a blog for every product or service we offer).
    
3. Streaming platform (011).
    
4. 3d multiplayer web based game engine with WASM & WebGPU+P2Pm frontend (Peer2Peer Mesh network with clustering) (RedX Game Engine/The Realms of Lairiah) + (custom GO backend).
    

# Conclusion

Overall EntropyCMS is a cutting edge content management system with high end performance, modularity, and next-gen post quantum compliance security, it is in the final stages of development and we will be releasing it on our organizations Github in Q1 of 2026.