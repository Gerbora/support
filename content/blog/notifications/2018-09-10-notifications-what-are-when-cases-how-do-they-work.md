---
layout: post
title:  "What are when cases & how do they work?"
uri: what-are-when-cases-how-do-they-work
tags: [notifications]
---

<p>
    When cases are a set of options that define situations when notifications should be fired. Each when case has a
    selected action type:
</p>

<!--more-->

<ol>
    <li>
        <strong>Variable in ranges</strong> - tracks when the value of variables moves to different ranges between
        normal, warning and error ranges and stays in a new range for a defined time.
    </li>
    <li>
        <strong>Getting data</strong> - situations when Trafikito starts getting data from your server. Not getting data
        event must be fired first.
    </li>
    <li>
        <strong>Not getting data</strong> - situations when Trafikito stops getting data from your server. Use it
        together with getting data type to get notifications when Trafikito starts getting data again.
    </li>
</ol>

<p>
    A single notification may have one or more when cases. A notification is triggered when any when cases are positive.
</p>

<p>
    <strong>Getting data event will never fire if not getting data event is not fired first</strong>. Always define both
    when cases <em>when</em> building notifications.
</p>
