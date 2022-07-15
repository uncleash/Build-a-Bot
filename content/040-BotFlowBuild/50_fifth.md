---
title: "Event Handling"
chapter: false
weight: 50
---

## Event Handling

![EventHandling](/images/EventHandling.jpg)

#### Disconnect

* There are 2 blocks in the Disconnect menu. Both indicate that the bot is done

* Exit Bot Flow is the default added to the flow and will end the Bot Flow. However, it does not end the interaction, this will return to the calling Architect flow (Inbound Call, Inbound Chat or Inbound Message) instead. Use when you are done with the bot, but want to still route to agent or call a new Bot Flow

* Disconnect indicates the interaction is done and will end it. It will not return to the calling Architect flow, but will end the call or messaging session

* Both are End of Flow actions, so should only be used when the bot is finished.

![DisconnectImg](/images/Disconnect.jpg)