---
title: Moving to Hetzner
abstract: My reason for choosing Hetzner as hosting provider.
icon: 🧳
date: 2026-01-23
---

In the past 10-ish years since I've started hosting applications, I've only used two different hosting providers: Versio and TransIP. I moved away from Versio to TransIP, because I needed to have control over the server instead of a simple DirectAdmin control panel. And now I've moved again, this time to Hetzner.

## Why TransIP?

I used to host all my applications, including public ones like this website, at home. To prevent my home IP from leaking I set up a proxy on a TransIP server. This was for me the way to go, just because of earlier experiences with their platform.

Over time, I became more and more aware that it just wasn't a good idea to have the entire internet access my home network. Not only security, but also reliability was an issue. My ISP changes my public IP once in a while (often after maintenance) and this website and [boodschrappen.nl](https://boodschrappen.nl) become unavailable. And with a power outage a few weeks ago it was enough; I had to migrate my public apps to an external server.

## Why Hetzner?

Simply because of the costs. I get a lot more resources for less money on Hetzner than I did on TransIP. And because I want to move my public applications out of my home I need a little more than 1 vCPU and 1 GB memory. On my Hetzner VPS I got 2 vCPUs and 4 GB memory. This was the cheapest option, but one tier higher (4 vCPUs and 8 GB memory) is still cheaper than the one from TransIP.

I did have some issues with setting up users, because I normally had a pre-defined (non-root) user on a TransIP VPS. I also have no experience with the Hetzner portal, so that might have played a role as well.

## In conclusion

In retrospect, I should have done this way earlier. I just never had the time or rather I just didn't feel like it. Migrating wasn't an issue really and everything is still running smoothly. The page you're currently reading is served from my new Hetzner VPS (if I haven't already migrated to somewhere else of course 😜).
