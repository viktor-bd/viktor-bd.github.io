---
layout: post
title: My First Steps in Home Automation
lead: A beginner's adventure in DIY home automation, containers, and microcontrollers.
---

**Hello, world!** This is my first IOT blog post; a story of learning, tinkering, and a few happy accidents along the way.
{: .message }

- toc
{: toc }

Like many tech enthusiasts, I love the idea of making my home smarter. I have no formal expertise in electronics or automation—just a curiosity about how things work and a willingness to tinker until they do (or don’t).

## Building a Home Server

My journey began when I acquired a used Lenovo ThinkCentre—a modest but reliable mini PC. With a bit of research, I discovered the magic of virtualization and decided to install **Proxmox**, a powerful and free hypervisor. This setup allowed me to experiment safely, spinning up virtual machines and containers for different purposes.

For those looking to get started, **CasaOS** is a fantastic open-source home server platform that simplifies managing containers and apps. With CasaOS running on Proxmox, I could deploy new services with just a few clicks.

## Containers for Everything

One of the most exciting parts of this journey has been learning to use Docker containers for modular home automation. Here are a few of my favorite setups so far:

- **Nginx Proxy Manager:** Makes it easy to manage and secure access to all my local services, with simple UI for SSL and reverse proxy rules.
- **Pi-hole:** Blocks ads and trackers across my entire network, improving privacy and speed for all devices.

It’s amazing how much you can achieve with just a few containers running side by side.

## Microcontrollers and ESPHome

Not content with just server-side tinkering, I picked up an **ESP32** microcontroller. Enter **ESPHome**! With a bit of YAML and some patience, I flashed the ESP32 and started experimenting with sensors and automations.

One of my first projects was turning the ESP32 into a real-time notifier and shopping list device. With a little setup, it could send updates straight to my phone—no cloud required! It’s oddly satisfying to see sensor data show up instantly on my mobile, knowing it’s all happening on a DIY device I programmed myself.

## The Plant Watering Project

My ambitions keep growing. Inspired by too many withered houseplants, I ordered cables and sensors online to build an automated plant watering system. The goal: have the ESP32 measure humidity and temperature, and trigger watering as needed.

I’m still in the early stages (waiting for parts in the mail!), but the idea of combining my server, containers, and microcontrollers into a cohesive home automation system is incredibly motivating.

## What’s Next?

I’m just getting started, and every experiment leads to new ideas and challenges. There’s a whole world of open-source projects, friendly communities, and clever solutions waiting to be discovered.

If you’re thinking about diving into home automation, my advice is simple: Start small, don’t be afraid to break things, and have fun with the process. I’ll be sharing more updates as my projects evolve!

3D Printing!?

* * *

Have questions, tips, or ideas for what I should try next? Leave a comment, or reach out on [GitHub](https://github.com/viktor-bd)!