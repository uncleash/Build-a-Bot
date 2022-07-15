---
title: "Flow & Data Blocks"
chapter: false
weight: 20
---

## Flow and Data Blocks

#### Flow Blocks

* Clear Slot is useful for setting the value again. For example, capturing a password for reset, you can use the same Password Slot more than once. Can also be useful to remove private data that you do not want in subsequent flows. The only input is the Slot name

* Set Intent can be used to hard code an Intent based on a decision. For example, if the previous flow passes the actual Intent, you can set it. It can also help when you want to jump from one Intent to another without having to capture a phrase. In this case, you might only have one Intent and only want to use the flow for Slot recognition. This could also be used with the Get Journey Segment block to set the intent based on the Predictive Engagement segment. The only input is the Intent name

* Neither can use variables to set the values

![FlowBlock](/images/FlowBlock.jpg)

#### Data Blocks

* The blocks in the Data section of the Toolbox can be used as normal

* Especially useful for looking up data mid conversation. For example, prompting for an Account Number in an Ask for Slot, then use a Data Action to see if it is a valid one. If not, use a loop to prompt again for the value.

* This also allows fulfilment of the customer intent in the flow.

![DataBlock](/images/DataBlock.jpg)
