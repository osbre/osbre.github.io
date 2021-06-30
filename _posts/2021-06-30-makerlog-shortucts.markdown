---
layout: page
title:  "Automating Makerlog with Apple Shortcuts"
date:   2021-06-30 01:45:51 +0300
# categories: jekyll update
---
## Prologue

I really like logging my daily tasks and keeping up with streaks.

But doing it from phone takes some efforts. By saying "efforts" I mean going throught the mess of visual actions - like opening the browser and searching for the website, then navigating it to find the right fields and so on...

So one day I thought:

> Can I have one icon on my home screen just for logging tasks? 

## Realization

In the next few steps I\'ll show you how you can make your own \"Makerlog\" shortcut, and place it on a home screen.

#### Step 1. Make a webhook

Makerlog has a nice [webhooks](https://getmakerlog.com/integrations/webhooks) feature.

What it basically does, it creates a special URL that you can use to post your tasks using the HTTP protocol. Let\'s make one:

1. Open [this URL](https://getmakerlog.com/integrations/webhooks) or click on the `Profile picture -> Integrations -> Webhooks`
2. Click on the *\"Create webhook\"* button
3. You\'ll see a generated URL, similar to the one shown below. Copy it.

![view after webhook was created](/images/makerlog-webhook-creation.png)

#### Step 2. Make a shortcut

1. Open to the [shortcuts app](https://apps.apple.com/us/app/shortcuts/id915249334) and click on the \"plus\" button