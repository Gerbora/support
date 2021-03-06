---
layout: post
title:  "How to change text in dashboard?"
uri: how-to-change-text-in-dashboard
tags: [dashboard]
---

<ol>
    <li>
        Go to single server view where you can see the box with text.
    </li>
    <li>
        Turn on the edit mode switch, which is on the bottom left of the single server view. Now you can view settings
        of any box, drag boxes around, add new or remove current.
    </li>
    <li>
        To edit a specific text, click the pencil icon on that box. Dialog with settings appear.
    </li>
    <li>
        Make sure the Text tab is selected on the top section of the dialog.
    </li>
    <li>
        Add any text together with variables. You can format text with available tools over the input. All available
        variables are on the bottom of the dialog. Click on any to copy and paste it as normal text into the input.
        Variables must be surrounded by pairs of curly braces like this: <span class="t-code">{% raw %}{{variable_name}}{% endraw %}</span>.
    </li>
    <li>
        Click save on the bottom right.
    </li>
    <li>
        Close the settings dialog with the button on the top right side of the dialog.
    </li>
    <li>
        Switch edit mode off.
    </li>
</ol>

<!--more-->

<p>
    How variables are rendered depends on the variable display type. It may be a string, number, base or percent.
</p>

<h4>Notes:</h4>

<ol>
    <li>Don’t forget to click <strong>Save</strong></li>
    <li>Changes will be applied to all members of the workspace.</li>
    <li>To save any changes you must have an admin or owner role in an active workspace.</li>
</ol>