
# ![Bot Framework Samples](./docs/media/BotFrameworkSamples_header.png)

### [Click here to find out what's new with Bot Framework](https://github.com/microsoft/botframework-sdk/blob/master/README.md)

## Overview

This branch contains samples for the released version of the **Microsoft Bot Framework V4 SDK** for [.NET](https://github.com/Microsoft/botbuilder-dotnet), [JS](https://github.com//microsoft/botbuilder-js) and [Python](https://github.com//microsoft/botbuilder-python). If you need samples for the Bot Framework _V3_ SDK, go [here](https://github.com/Microsoft/BotBuilder-Samples/tree/v3-sdk-samples).

## Getting the samples

To use the samples, clone this GitHub repository using Git.

```bash
    git clone https://github.com/Microsoft/BotBuilder-Samples.git
    cd BotBuilder-Samples
```

## Sample lists

Samples are designed to illustrate scenarios you'll need to implement to build great bots!

- [Bot essentials](#bot-essentials)
- [Advanced bots](#advanced-bots)
- [Authentication samples](#authentication-samples)
- [QnA Maker samples](#qna-maker-samples)
- [Teams samples](#teams-samples)
- [Skills samples](#skills-samples)


### Bot Essentials

| Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|2.echo-bot             | Demonstrates how to receive and send messages.                                 |[Core][cs#2] |[JS][js#2], [TS][ts#2]|[Python][py#2]
|3.welcome-user         | Introduces activity types and provides a welcome message on conversation update activity. |[Core][cs#3] |[JS][js#3], [TS][ts#3]|[Python][py#3]
|5.multi-turn-prompt    | Demonstrates how to use waterfall dialog, prompts, and component dialog to create a simple interaction that asks the user for name, age, and prints back that information.          |[Core][cs#5] |[JS][js#5], [TS][ts#5] |[Python][py#5]
|6.using-cards          | Introduces all card types including thumbnail, audio, media etc. Builds on Welcoming user + multi-prompt bot by presenting a card with buttons in welcome message that route to appropriate dialog.     |[Core][cs#6] |[JS][js#6], [TS][ts#6] |[Python][py#6]
|7.using-adaptive-cards | Demonstrates how the multi-turn dialog can use a card to get user input for name and age. |[Core][cs#7] |[JS][js#7] |[Python][py#7]
|8.suggested-actions    | Demonstrates how to enable your bot to present buttons that the user can tap to provide input.                                      |[Core][cs#8] |[JS][js#8] |[Python][py#8]
|13.core-bot            | Core bot shows how to use cards, dialog, and Language Understanding (LUIS).                         |[Core][cs#13], [Web][wa#13]|[JS][js#13], [TS][ts#13]|[Python][py#13]
|14.nlp-with-dispatch   | Demonstrates how to dispatch across LUIS and QnA Maker.                            |[Core][cs#14]|[JS][js#14]|[Python][py#14]
|15.handling-attachments| Demonstrates how to listen for/handle user provided attachments.                |[Core][cs#15]|[JS][js#15]|[Python][py#15]
|16.proactive-messages  | Demonstrates how to send proactive messages to users.                           |[Core][cs#16]|[JS][js#16], [TS][ts#16]|[Python][py#16]
|17.multilingual-bot    | Using translate middleware to support a multi-lingual bot. Demonstrates custom middleware. |[Core][cs#17]|[JS][js#17]|[Python][py#17]
|40.timex-resolution    | Demonstrates various ways to parse and manipulate the TIMEX expressions you get from LUIS and the [DateTimeRecognizer](https://github.com/Microsoft/recognizers-text) used by the DateTimePrompt. |[Core][cs#40] |[JS][js#40]|[Python][py#40]
|43.complex-dialog      | Demonstrates different ways for composing dialogs. |[Core][cs#43]|[JS][js#43] |[Python][py#43]
|44.prompt-for-user-input | Demonstrates how to implement your own _basic_ prompts to ask the user for information. |[Core][cs#44]|[JS][js#44]|[Python][py#44]
|45.state-management    | Demonstrates how to use state management and storage objects to manage and persist state. | [Core][cs#45] | [JS][js#45]   |[Python][py#45]

### Advanced bots


| Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|1.console-echo         | Introduces the concept of adapter and demonstrates a simple echo bot on console adapter and how to send a reply and access the incoming message.           |[Core][cs#1] |[JS][js#1], [TS][ts#1] |[Python][py#1]
|1.browser-echo         | Demonstrates how to host a bot in the browser using Web Chat and a custom Web Chat Adapter.   |  | [ES6][es#1]  |
|19.custom-dialogs      | Demonstrates complex conversation flow using the Dialogs library. |[Core][cs#19]|[JS][js#19]|[Python][py#19]
|21.corebot-app-insights     | Demonstrates how to add telemetry logging to your bot, storing telemetry within Application Insights.|[Core][cs#21] |[JS][js#21] |
|23.facebook-events     | Integrate and consume Facebook specific payloads, such as post-backs, quick replies and opt-in events.|[Core][cs#23] |[JS][js#23] |[Python][py#23]
|42.scaleout            | Demonstrates how you can build your own state solution from the ground up that supports scaled out deployment with ETag based optimistic locking. |[Core][cs#42] |    |[Python][py#42]
|47.inspection    | Demonstrates how to use middleware to allow the Bot Framework Emulator to debug traffic into and out of the bot in addition to looking at the current state of the bot. | [Core][cs#47] | [JS][js#47]   |[Python][py#47]
|70.styling-webchat     | This sample shows how to create a web page with custom Web Chat component.|         | [ES6][es#70]         |

### Auth Samples

| Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|18.bot-authentication  | Bot that demonstrates how to integrate OAuth providers.                  |[Core][cs#18]|[JS][js#18]|[Python][py#18]
|24.bot-auth-msgraph    | Demonstrates bot authentication capabilities of Azure Bot Service. Demonstrates utilizing the Microsoft Graph API to retrieve data about the user.|[Core][cs#24] |[JS][js#24] |[Python][py#24]
|46.teams-auth    | Demonstrates how to use authentication for a bot running in Microsoft Teams. | [Core][cs#46] | [JS][js#46]   |[Python][py#46]

### QnAMaker Samples

| Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|11.qnamaker              | Demonstrates how to use QnA Maker to have simple single-turn conversations     |[Core][cs#11]|[JS][js#11]      |[Python][py#11]
|49.qnamaker-all-features | Demonstrates how to integrate Multiturn and Active learning in a QnA Maker bot.  This also demonstrates the QnAMakerDialog class. |[Core][cs#49]|[JS][js#49]      |

### Teams Samples

| Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|46.teams-auth    | Demonstrates how to use authentication for a bot running in Microsoft Teams. | [Core][cs#46] | [JS][js#46]   |[Python][py#46] |
|50.teams-messaging-extensions-search     |  A Messaging Extension that accepts search requests and returns results.|[Core][cs#50]|[JS][js#50]          |[Python][py#50] |
|51.teams-messaging-extensions-action     |  A Messaging Extension that accepts parameters and returns a card.  Also, how to receive a forwarded message as a parameter in a Messaging Extension.|[Core][cs#51]|[JS][js#51]          |[Python][py#51] |
|52.teams-messaging-extensions-search-auth-config     | A Messaging Extension that has a configuration page, accepts search requests and returns results after the user has signed in.|[Core][cs#52]|[JS][js#52]          |
|53.teams-messaging-extensions-action-preview     | Demonstrates how to create a Preview and Edit flow for a Messaging Extension.|[Core][cs#53]|[JS][js#53]          |[Python][py#53] |
|54.teams-task-module     | Demonstrates how to retrieve a Task Module, and values from cards in the Task Module, for a Messaging Extension.|[Core][cs#54]|[JS][js#54]          |[Python][py#54] |
|55.teams-link-unfurling     | A Messaging Extension that performs link unfurling.|[Core][cs#55]|[JS][js#55]          |[Python][py#55] |
|56.teams-file-upload     | Demonstrates how to obtain file consent, and upload files to Teams from a bot. Also, how to receive a file sent to a bot.|[Core][cs#56]|[JS][js#56]          |[Python][py#56] |
|57.teams-conversation-bot     | Demonstrates various features of bots on Teams: message all members in a Team or Channel, @mention a user from a bot, update previously sent messages, etc. |[Core][cs#57]|[JS][js#57]          |[Python][py#57] |
|58.teams-start-new-thread-in-channel     | Demonstrates creating a new thread in a channel. |[Core][cs#5]|[JS][js#58]          |[Python][py#58] |

### Skills Samples

| Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|80.skills-simple-bot-to-bot | This sample shows how to connect a skill to a skill consumer.       | [Core][cs#80] | [JS][js#80]     |[Python][py#80] |
|81.skills-skilldialog       | This sample shows how to connect a skill to a skill dialog consumer.| [Core][cs#81] | [JS][js#81]     |[Python][py#81] |

[cs#1]:samples/csharp_dotnetcore/01.console-echo
[cs#2]:samples/csharp_dotnetcore/02.echo-bot
[cs#3]:samples/csharp_dotnetcore/03.welcome-user
[cs#5]:samples/csharp_dotnetcore/05.multi-turn-prompt
[cs#6]:samples/csharp_dotnetcore/06.using-cards
[cs#7]:samples/csharp_dotnetcore/07.using-adaptive-cards
[cs#8]:samples/csharp_dotnetcore/08.suggested-actions
[cs#11]:samples/csharp_dotnetcore/11.qnamaker
[cs#12]:samples/csharp_dotnetcore/11a.qnamaker
[cs#13]:samples/csharp_dotnetcore/13.core-bot
[cs#13.b]:samples/csharp_dotnetcore/13.core-bot.tests
[cs#14]:samples/csharp_dotnetcore/14.nlp-with-dispatch
[cs#15]:samples/csharp_dotnetcore/15.handling-attachments
[cs#16]:samples/csharp_dotnetcore/16.proactive-messages
[cs#17]:samples/csharp_dotnetcore/17.multilingual-bot
[cs#18]:samples/csharp_dotnetcore/18.bot-authentication
[cs#19]:samples/csharp_dotnetcore/19.custom-dialogs
[cs#21]:samples/csharp_dotnetcore/21.corebot-app-insights
[cs#23]:samples/csharp_dotnetcore/23.facebook-events
[cs#24]:samples/csharp_dotnetcore/24.bot-authentication-msgraph
[cs#40]:samples/csharp_dotnetcore/40.timex-resolution
[cs#42]:samples/csharp_dotnetcore/42.scaleout
[cs#43]:samples/csharp_dotnetcore/43.complex-dialog
[cs#44]:samples/csharp_dotnetcore/44.prompt-users-for-input
[cs#45]:samples/csharp_dotnetcore/45.state-management
[cs#46]:samples/csharp_dotnetcore/46.teams-auth
[cs#47]:samples/csharp_dotnetcore/47.inspection
[cs#49]:samples/csharp_dotnetcore/49.qnamaker-all-features
[cs#50]:samples/csharp_dotnetcore/50.teams-messaging-extensions-search
[cs#51]:samples/csharp_dotnetcore/51.teams-messaging-extensions-action
[cs#52]:samples/csharp_dotnetcore/52.teams-messaging-extensions-search-auth-config
[cs#53]:samples/csharp_dotnetcore/53.teams-messaging-extensions-action-preview
[cs#54]:samples/csharp_dotnetcore/54.teams-task-module
[cs#55]:samples/csharp_dotnetcore/55.teams-link-unfurling
[cs#56]:samples/csharp_dotnetcore/56.teams-file-upload
[cs#57]:samples/csharp_dotnetcore/57.teams-conversation-bot
[cs#58]:samples/csharp_dotnetcore/58.teams-start-new-thread-in-channel
[cs#80]:samples/csharp_dotnetcore/80.skills-simple-bot-to-bot
[cs#81]:samples/csharp_dotnetcore/81.skills-skilldialog

[wa#13]:samples/csharp_webapi/13.core-bot

[es#1]:samples/javascript_es6/01.browser-echo
[es#70]:samples/javascript_es6/70.styling-webchat

[ts#0]:samples/typescript_nodejs/00.empty-bot
[ts#1]:samples/typescript_nodejs/01.console-echo
[ts#2]:samples/typescript_nodejs/02.echo-bot
[ts#3]:samples/typescript_nodejs/03.welcome-users
[ts#5]:samples/typescript_nodejs/05.multi-turn-prompt
[ts#6]:samples/typescript_nodejs/06.using-cards
[ts#13]:samples/typescript_nodejs/13.core-bot
[ts#16]:samples/typescript_nodejs/16.proactive-messages
[ts#52]:https://github.com/Microsoft/AI/tree/master/templates/Enterprise-Template


[js#1]:samples/javascript_nodejs/01.console-echo
[js#2]:samples/javascript_nodejs/02.echo-bot
[js#3]:samples/javascript_nodejs/03.welcome-users
[js#5]:samples/javascript_nodejs/05.multi-turn-prompt
[js#6]:samples/javascript_nodejs/06.using-cards
[js#7]:samples/javascript_nodejs/07.using-adaptive-cards
[js#8]:samples/javascript_nodejs/08.suggested-actions
[js#11]:samples/javascript_nodejs/11.qnamaker
[js#12]:samples/javascript_nodejs/11a.qnamaker
[js#13]:samples/javascript_nodejs/13.core-bot
[js#14]:samples/javascript_nodejs/14.nlp-with-dispatch
[js#15]:samples/javascript_nodejs/15.handling-attachments
[js#16]:samples/javascript_nodejs/16.proactive-messages
[js#17]:samples/javascript_nodejs/17.multilingual-bot
[js#18]:samples/javascript_nodejs/18.bot-authentication
[js#19]:samples/javascript_nodejs/19.custom-dialogs
[js#21]:samples/javascript_nodejs/21.corebot-app-insights
[js#23]:samples/javascript_nodejs/23.facebook-events
[js#24]:samples/javascript_nodejs/24.bot-authentication-msgraph
[js#40]:samples/javascript_nodejs/40.timex-resolution
[js#43]:samples/javascript_nodejs/43.complex-dialog
[js#44]:samples/javascript_nodejs/44.prompt-for-user-input
[js#45]:samples/javascript_nodejs/45.state-management
[js#46]:samples/javascript_nodejs/46.teams-auth
[js#47]:samples/javascript_nodejs/47.inspection
[js#49]:samples/javascript_nodejs/49.qnamaker-all-features
[js#50]:samples/javascript_nodejs/50.teams-messaging-extensions-search
[js#51]:samples/javascript_nodejs/51.teams-messaging-extensions-action
[js#52]:samples/javascript_nodejs/52.teams-messaging-extensions-search-auth-config
[js#53]:samples/javascript_nodejs/53.teams-messaging-extensions-action-preview
[js#54]:samples/javascript_nodejs/54.teams-task-module
[js#55]:samples/javascript_nodejs/55.teams-link-unfurling
[js#56]:samples/javascript_nodejs/56.teams-file-upload
[js#57]:samples/javascript_nodejs/57.teams-conversation-bot
[js#58]:samples/javascript_nodejs/58.teams-start-new-thread-in-channel
[js#80]:samples/javascript_nodejs/80.skills-simple-bot-to-bot
[js#81]:samples/javascript_nodejs/81.skills-skilldialog

[py#1]:samples/python/01.console-echo
[py#2]:samples/python/02.echo-bot
[py#3]:samples/python/03.welcome-user
[py#5]:samples/python/05.multi-turn-prompt
[py#6]:samples/python/06.using-cards
[py#7]:samples/python/07.using-adaptive-cards
[py#8]:samples/python/08.suggested-actions
[py#11]:samples/python/11.qnamaker
[py#13]:samples/python/13.core-bot
[py#14]:samples/python/14.nlp-with-dispatch
[py#15]:samples/python/15.handling-attachments
[py#16]:samples/python/16.proactive-messages
[py#17]:samples/python/17.multilingual-bot
[py#18]:samples/python/18.bot-authentication
[py#19]:samples/python/19.custom-dialogs
[py#21]:samples/python/21.corebot-app-insights
[py#23]:samples/python/23.facebook-events
[py#24]:samples/python/24.bot-authentication-msgraph
[py#40]:samples/python/40.timex-resolution
[py#42]:samples/python/42.scaleout
[py#43]:samples/python/43.complex-dialog
[py#44]:samples/python/44.prompt-for-user-input
[py#45]:samples/python/45.state-management
[py#46]:samples/python/46.teams-auth
[py#47]:samples/python/47.inspection
[py#50]:samples/python/50.teams-messaging-extensions-search
[py#51]:samples/python/51.teams-messaging-extensions-action
[py#52]:samples/python/52.teams-messaging-extensions-search-auth-config
[py#53]:samples/python/53.teams-messaging-extensions-action-preview
[py#54]:samples/python/54.teams-task-module
[py#55]:samples/python/55.teams-link-unfurling
[py#56]:samples/python/56.teams-file-upload
[py#57]:samples/python/57.teams-conversation-bot
[py#58]:samples/python/58.teams-start-thread-in-channel
[py#80]:samples/python/80.skills-simple-bot-to-bot
[py#81]:samples/python/81.skills-skilldialog

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Reporting Security Issues
Security issues and bugs should be reported privately, via email, to the Microsoft Security Response Center (MSRC) at [secure@microsoft.com](mailto:secure@microsoft.com). You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message. Further information, including the [MSRC PGP](https://technet.microsoft.com/en-us/security/dn606155) key, can be found in the [Security TechCenter](https://technet.microsoft.com/en-us/security/default).

Copyright (c) Microsoft Corporation. All rights reserved.
