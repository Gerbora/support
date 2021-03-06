---
layout: post
title:  "How to change the title or y-axis of the chart?"
uri: how-to-change-the-title-or-y-axis-of-the-chart
tags: [dashboard]
---

<ol>
    <li>
        Go to single server view where you can see the box with the chart.
    </li>
    <li>
        Turn on the edit mode switch, which is on the bottom left of single server view. Now you can view settings of
        any box, drag boxes around, add new or remove current.
    </li>
    <li>
        To edit a specific chart, click the pencil icon on it. Dialog with settings appears.
    </li>
    <li>
        Scroll down to the “Optional settings” section and edit the title. You can use text together with any variables.
        Variables must be surrounded by pairs of curly braces like this: {{variable_name}}. Variable will be replaced
        with the current value. On the bottom of the same view, you can see a cloud of chips with all variables. Click
        on anyone to copy and paste it in the title field.
    </li>
    <li>
        Click save on the bottom right.
    </li>
    <li>
        Close the settings dialog with the button on the top right of the dialog.
    </li>
    <li>
        Switch edit mode off.
    </li>
</ol>
<!--more-->

<p>
    While adding a variable in the title you can see a rendered preview with the current value of the variable. How
    variable is rendered depends on the <strong>variable display type</strong>. It may be a <strong>string</strong>,
    <strong>number</strong>, <strong>base </strong>or <strong>percent</strong>.
</p>


<h4>Notes:</h4>
<ul>
    <li>
        Layout changes are saved automatically.
    </li>
    <li>
        Changes will be applied to all members of the workspace.
    </li>
    <li>
        To save any changes you must have an admin or owner role in an active workspace.
    </li>
</ul>