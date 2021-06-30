---
layout: page
title:  "Automating Makerlog with Apple Shortcuts"
date:   2021-06-30
---

1. [Introduction](#introduction)
1. [Implementation](#implementation)
1. [Demo](#demo-screenshots)

## Introduction

I like logging my daily tasks and keeping up with streaks, but doing it from the phone takes some effort. By saying "effort" I mean going through the mess of visual actions each time you want to log a task. 

So one day I thought:

> Can I have one icon on my home screen just for logging tasks? 

## Implementation

In the next few steps I\'ll show you how you can make your own \"Makerlog\" shortcut, and place it on a home screen as an icon.

#### Step 1. Make a webhook

<!-- Makerlog has a nice [webhooks](https://getmakerlog.com/integrations/webhooks) feature. -->

<!-- What it basically does, it creates a special URL that you can use to post your tasks using the HTTP protocol. Let\'s make one: -->

1. Open [this URL](https://getmakerlog.com/integrations/webhooks) or click on the `Profile picture -> Integrations -> Webhooks`
2. Click on the *\"Create webhook\"* button
3. You\'ll see a generated URL, similar to the one shown below. Copy it.

![view after webhook was created](/images/makerlog-webhook-creation.png)

#### Step 2. Make a shortcut

Open to the [shortcuts app](https://apps.apple.com/us/app/shortcuts/id915249334) and tap on the \"plus\" button. Now add the following actions:

\"**Ask for input**\"

![makerlog shortcut "ask" action](/images/makerlog-automation-ask.png)

\"**URL**\". Paste your webhook URL in the value input.

![makerlog shortcut "URL" action](/images/makerlog-automation-url.png)

\"**Get Contents of URL**\". Choose "Show more" and set the following parameters:

![makerlog shortcut "Get Contents of URL" action](/images/makerlog-automation-content.png)


#### Step 3. Add shortcut to the home screen

Tap on the "Three dots" and choose `Add to Home Screen`.

You can also set the icon and the name of your shortcut.

![Shortcut options menu](/images/makerlog-automation-options.png)

#### Demo (screenshots)

![Makerlog automation demo](/images/makerlog-automation-demo.jpg)