---
layout: post
title:  "What will happen if I delete a data source which is in use?"
uri: what-will-happen-if-i-delete-a-data-source-which-is-in-use
tags: [data sources]
---

<p>
    Deleting data sources will delete it’s variables and logs. Logs and variables are removed for this data source only.
    Other data sources will be kept unmodified. If the data source does not have any variables defined or defined
    variables are not in use anywhere - nothing else will happen.
</p>

<!--more-->

<p>
    If this data source does have variables defined and those variables are in use:
</p>
<ul>
    <li>
        In the text boxes, notification email and anywhere it is rendered as text, you will see the variable name
        instead of a value.
    </li>
    <li>
        In charts variables will have no logs and depending on if the chart have other active variables, it will display
        an empty chart for the deleted variable or just the message <strong>No data for this time interval</strong>.
    </li>
</ul>