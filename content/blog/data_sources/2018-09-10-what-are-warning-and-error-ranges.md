---
layout: post
title:  "What are warning and error ranges?"
uri: what-are-warning-and-error-ranges
tags: [data sources]
---

<p>
    Warning and error range settings define when numeric value of a variable is in <span class="t-normal">normal</span>,
    <span class="t-warn">warning</span> or <span class="t-error">error</span> range. You can add several ranges for each
    variable with numeric display type.
</p>

<!--more-->

<p>
    Each range has <strong>from</strong> and <strong>to</strong> values. You can use these ranges in the notifications
    settings. E.g. if you want to get an email when the average load of the server is in a warning range, you have to
    have data source to get this information, variable to hold specific number from the output, numeric display type and
    warning range defined.
</p>

<p>
    Then you can use such variable in notifications setting to send emails when a value is in a warning or error range
    for defined count of minutes.
</p>

<!-- todo [notification settings link] -->
