---
pagename: Overview
Keywords:
sitesection: Documents
categoryname: "Conversational AI"
documentname: Bots Status
permalink: bots-status-overview.html
indicator: both
---

Use the Bots Status application to check the status of all your bots from a single location. 

You can use the application to monitor and manage both normal (custom) bots and post-conversation survey bots.

<img class="fancyimage" style="width:1000px" src="img/ConvoBuilder/botsStatus_dashboard.png">

### Access Bots Status

{: .important}
To access the Bots Status application, you must have the Bot Status Access [permission](bot-accounts-permissions.html).

**To access the Bot Status application**

1. On the left sidebar in Conversational Cloud, click the <img style="width:30px" src="img/ConvoBuilder/icon_cb.png"> icon.
2. In the Conversational AI dashboard, click **Bots Status**.

### Bot agent connector statuses

An agent connector can have one of the following statuses:

* **Ready to Start**: The connector was added successfully, but it hasn't been started for the first time.
* **Online**: The connector is running, and all end-to-end connections are working well.
* **Offline**: At least one underlying component isn't working, causing end-to-end connections not to function. The connector is in an error state and isn't running.
* **Stopped**: The connector isn't running because it was manually stopped.