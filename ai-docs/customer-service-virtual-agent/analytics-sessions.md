---
title: "Sessions page"
description: "Learn about the Dynamics 365 Virtual Agent for Customer Service Sessions page."
keywords: ""
ms\.date: 05/14/2019
ms.service:
  - "dynamics-365-ai"
ms.topic: article
ms.assetid: 
author: stevesaunders1952
ms.author: stevesaunders1952
manager: shellyha
---

# Sessions page

   > ![Sessions page](media/sessions-page.png)

The sessions page lets you download information from your customer service sessions from the last 30 days, up to 1000 sessions.

The downloaded file contains the following information: 

- SessionID: A unique identifier per session 

- StartDateTime: Time at which the session started. Entries are sorted by this column in descending order 

- Initial Message: First message typed by the user

- Topic Name: Name of the last authored topic which was triggered in this session 

- Chat Transcript: Transcript of the session in the following format:
    - User says-Bot says structure
    - Conversation turns separated by semicolon
    - Bot says does not include the options presented to the user

    Example: “User says: store hours; Bot says: Which store are you asking about?; User says: Bellevue; Bot says: Bellevue store is open from 10am to 7pm every day.;”

- Session Outcome: Outcome of the session (Resolved, Escalated, Abandoned, Unengaged)

- TopicID: A unique identifier of the last authored topic triggered in this session 
