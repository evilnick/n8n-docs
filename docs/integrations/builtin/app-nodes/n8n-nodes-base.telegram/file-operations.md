---
#https://www.notion.so/n8n/Frontmatter-432c2b8dff1f43d4b1c8d20075510fe4
title: File operations
description: Documentation for the File operations in the Telegram node in n8n, a workflow automation platform. Includes details to configure all File operations.
contentType: integration
priority: critical
---

# Telegram File operations

Use this operation to get a file from Telegram. Refer to [Telegram](/integrations/builtin/app-nodes/n8n-nodes-base.telegram/) for more information on the Telegram node itself.

## Get File

Use this operation to get a file from Telegram using the Bot API [getFile](https://core.telegram.org/bots/api#getfile){:target=_blank .external-link} method.

Enter these parameters:

* **Credential to connect with**: Create or select an existing [Telegram credential](/integrations/builtin/credentials/telegram/).
* **Resource**: Select **File**.
* **Operation**: Select **Get**.
* **File ID**: Enter the ID of the file you want to get.
* **Download**: Choose whether you want the node to download the file (turned on) or not (turned off).

Refer to the Telegram Bot API [getFile](https://core.telegram.org/bots/api#getfile){:target=_blank .external-link} documentation for more information.