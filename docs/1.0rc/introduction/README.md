---
description: >-
  Battery Webhook is an app that lets you send your battery info to popular
  services using webhooks.
---

# Introduction

To use it, you'll need to configure Battery Webhook with a webhook to push to, as well as filling out some basic info on how you would like to appear to the webhook (such as a display name).

If you already have a webhook you want to provide to Battery Webhook, see [Quick Start](quick-start.md). Otherwise, continue reading.

### What is a webhook?

A **webhook** is a method of communication to a web application. It allows an application to send real-time data to another application whenever a specific event occurs.

In the case of Battery Webhook, the real-time data is your device's battery information, and the event is either manual or automated. The services we support sending to are documented in the next page, [Supported Services](../supported-services/).

### Why should I use this?

Battery Webhook can send something like the following whenever you open the app and manually tap Send Battery Info:

<div data-full-width="false">

<figure><img src="../../.gitbook/assets/image (9).png" alt="" width="563"><figcaption><p>Battery Webhook's output to a Discord webhook when manually triggered</p></figcaption></figure>

</div>

That's fine and all, but not very useful unless you feel like opening the app every time you want to report battery info. **However**, Battery Webhook supports automations! So, you can have it send battery info whenever you plug in, unplug or fully charge your device, as seen below:

<figure><img src="../../.gitbook/assets/image (11).png" alt="" width="563"><figcaption><p>Battery Webhook's output to a Discord webhook when triggered by plugging in, fully charging, then unplugging the device</p></figcaption></figure>

Automations allow Battery Webhook to inform you about power state changes for devices that you may want to be informed about, like in these examples:

* You have a MacBook that you need on and charged at all times and want to know if it loses power
* You're using an old iPhone or iPad as an indoor camera and must know if you it gets unplugged
* You want to see exactly how long your device takes to charge
* You simply want to share with friends
* Much more

### What about my privacy?

Battery Webhook collects the following information automatically:&#x20;

* Battery level (example: 15%)
* Device model (example: iPhone 15 Pro Max)
* Device name (example: iPhone - but can be customized)
* OS version (example: 17.2)
* Date and time

It also has you provide the following information:

* Display Name (required, doesn't need to be a real name or username)
* Pronoun (optional, only used for automations)

You can opt out of sending some of the collected into to webhooks, which is covered in [Further configuring Battery Webhook](../supported-services/configuring-a-discord-webhook/further-configuring-battery-webhook.md). For most users, however, this isn't needed.
