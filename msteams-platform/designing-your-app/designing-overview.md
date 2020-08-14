---
title: Designing your Microsoft Teams app overview
author: heath-hamilton
description: Overview on how to design a Microsoft Teams app.
---
# Designing your Microsoft Teams app

Designing Teams apps is similar to designing other types of apps—but also a little different.

Follow these guidelines—which include best practices, UI toolkits, and samples—to help you quickly make the right design decisions for your app.

> [!NOTE]
> These guidelines are primarily for designing desktop apps.

## Before you begin

You can't design a great Teams app without a fundamental understanding of what the app is supposed to do and how you think people will use it. Before opening your design tools, make sure you've properly [planned your app]().

## General principles

A well-designed Teams app has the following characteristics:

* Promotes collaboration
* Focuses only on core activities and scenarios
* Appears either native to Teams or completely distinct (not a blend of color schemes, styles, and controls)
* Easy to use
* Inclusive of all backgrounds and abilities
* Accessible
* Has a clear purpose (through expressive app icons and usable documentation)

## Creating a cohesive look and feel

Apps extend Teams features and functionality using one or more platform [capabilities](../concepts/capabilities-overview.md). Your app presents these capabilities—whether it's a tab, messaging extension, bot, or webhook—with common and Teams-centric UI components.

Designing your app requires knowing what UI works for certain capabilities (and what doesn't). For example, while multi-level navigation is fine for websites, it isn't ideal for a Teams tab because it probably isn't focusing only on core activities and scenarios.

Your design also must thread UI components together in a way that feels natural not only to your use case but also within Teams. (This is especially true if your app has more than one capability, such as a bot replying with a link to a tab that has a form to complete.)

## Tabs

Tabs are canvases for web-based content. Unlike a standard web app or website, they work best when displaying a limited set of content or tasks. [See tab design guidelines](../designing-your-app/designing-tabs.md)

## Messaging extensions

Messaging extensions are shortcuts for sharing information in a conversation in the form of a content-rich card, which can include a complex task or simple GIF. [See messaging extension design guidelines](../designing-your-app/designing-messaging-extensions.md)

## Bots

Bots are conversational interfaces that perform a narrow set of tasks proactively or in response to a message. [See bot design guidelines](../designing-your-app/designing-bots.md)

## Webhooks and connectors

Webhooks and connectors send notifications and alerts to team channels and chats (typically with cards). [See webhooks and connectors design guidelines](../designing-your-app/designing-connectors.md)

## UI components

Each capability in your Teams app needs a UI. There's a variety of UI components you can use, but some components make more sense than others in Teams.

For example, you can use [*cards*](../designing-your-app/designing-cards.md) to display rich content with messaging extensions, bots, and incoming webhooks. A [*task module*](../designing-your-app/designing-task-modules.md) is another Teams-centric component; it's essentially a card that allows users to take action (for example, complete a form). [INCLUDE LINKS]

## Resources

* Tool kit – resources & assets (most WIP)
* [Adaptive card designer](https://adaptivecards.io/designer)
* UI components – Stardust site (https://fluentsite.z22.web.core.windows.net/)
* Platform high value components (WIP)
