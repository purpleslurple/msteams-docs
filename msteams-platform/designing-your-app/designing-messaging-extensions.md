---
title: Designing messaging extensions in Microsoft Teams
author: heath-hamilton
description: Guidance and best practices for designing messaging extensions in a Microsoft Teams app.
---
# Designing Teams messaging extensions

People primarily use messaging extensions anywhere they can compose or view messages in Teams. Messaging extensions are shortcuts for inserting content and initiating workflows in a conversation.

From a design perspective, there are a couple types of messaging extensions to understand:

* **Action commands**: Initiate a workflow in the compose box, command box, or based on a posted message. Once initiated, users are commonly presented with a modal (i.e., task module) to collect input that's processed and posted in a conversation.
* **Search commands**: Look for content outside Teams from the compose box and share it in a conversation (typically as a card). Also search for external content in the command box to view, interact with, or copy for later.

## Best practices

Use these as checklists when designing your messaging extension.

### Dos

* **Keep it simple**. A messaging extension should be lightweight and fast or it loses its utility.
* **Use only a single parameter for search commands**. While you can have multiple search parameters, more than one makes the messaging extension interface more complicated than it should be.
* **Limit the card size for search results**. Since each search results display as a list of cards, save most of your information, images, and formatting for the card your user selects.

### Don'ts

* **Include optional parameters in your search commands**. People can feel obligated to complete every parameter before initiating the search.
* **Forget to optimize your cards**. Each messaging extension produces a card. Since it’s the last thing your user sees, make sure the cards look appealing, have useful information, and are easy to share.

## Setup and authentication

If your messaging extension includes an onboarding workflow, your design may need to account for a sign-in page, configuration dialog, and welcome screen.

## Search commands

Provide descriptions + example scenarios/screenshots

Design sketch artboard for different layouts (eg. list view, grid view)

Guidelines, screenshots (list and grid views), links to resources.

Links to card and task module guidelines as needed.

## Action commands

Provide descriptions + example scenarios/screenshots

Refer to task module for detailed design

## Link unfurling

Your messaging extension can support simple link unfurling, which displays a card when a user enters or pastes a URL from a recognized domain in the compose box.

You can use the following card types with link unfurling:

* Thumbnail
* Hero
* Office 365 Connector
* Adaptive Card

## Mobile considerations

Text

## Real-world examples

* [Azure DevOps](https://teams.microsoft.com/l/app/com.microsoft.teamspace.tab.vsts?source=store-copy-link)

## Resources

* Sketch files
* Developer section of ME (how to get started)
* Developer section of task module (how to get started)
* Designer section of task module
