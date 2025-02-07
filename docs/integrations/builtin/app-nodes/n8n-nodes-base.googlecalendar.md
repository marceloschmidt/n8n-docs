---
#https://www.notion.so/n8n/Frontmatter-432c2b8dff1f43d4b1c8d20075510fe4
title: Google Calendar node documentation
description: Learn how to use the Google Calendar node in n8n. Follow technical documentation to integrate Google Calendar node into your workflows.
contentType: integration
priority: high
---

# Google Calendar node

Use the Google Calendar node to automate work in Google Calendar, and integrate Google Calendar with other applications. n8n has built-in support for a wide range of Google Calendar features, including adding, retrieving, deleting and updating calendar events.

On this page, you'll find a list of operations the Google Calendar node supports and links to more resources.

/// note | Credentials
Refer to [Google Calendar credentials](/integrations/builtin/credentials/google/) for guidance on setting up authentication. 
///

## Operations

* **Calendar**
    * **Availability**: If a time-slot is available in a calendar
* **Event**
    * **Create**: Add an event to calendar
    * **Delete**: Delete an event
    * **Get**: Retrieve an event
    * **Get Many**: Retrieve all events from a calendar
    * **Update**: Update an event

## Templates and examples

<!-- see https://www.notion.so/n8n/Pull-in-templates-for-the-integrations-pages-37c716837b804d30a33b47475f6e3780 -->
[[ templatesWidget(title, 'google-calendar') ]]

## Related resources

n8n provides a trigger node for Google Calendar. You can find the trigger node docs [here](/integrations/builtin/trigger-nodes/n8n-nodes-base.n8n-nodes-base.googlecalendartrigger/).

Refer to [Google Calendar's documentation](https://developers.google.com/calendar/api/v3/reference){:target=_blank .external-link} for more information about the service.

View [example workflows and related content](https://n8n.io/integrations/Google Calendar/){:target=_blank .external-link} on n8n's website.
