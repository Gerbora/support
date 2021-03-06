---
layout: post
title:  "Options when the action type for when cases are variables in ranges?"
uri: options-when-the-action-type-for-when-cases-are-variables-in-ranges
tags: [notifications]
---

<p>
    While creating notifications you have to add some <em>when</em> cases. When cases defines <em>when</em> to trigger
    the action of notifications. If the action type is set to a <em>Variable in a range</em> you will get these options
    to make adjustments:
</p>

<!--more-->

<ol>
    <li>
        <strong>Variable to track</strong> - select any variable defined in the data sources. This when case will track
        the range of the value for the selected variable.
    </li>
    <li>
        <strong>Range change</strong> - when a value changes it may move to different value ranges. This option
        determines what changes to action.
        <ol type="i">
            <li><span class="t-normal">Normal</span> → <span class="t-warn">warn</span></li>
            <li><span class="t-normal">Normal</span> → <span class="t-error">error</span></li>
            <li><span class="t-normal">Normal</span> → <span class="t-neutral">any</span></li>
            <li><span class="t-warn">Warn</span> → <span class="t-normal">normal</span></li>
            <li><span class="t-warn">Warn</span> → <span class="t-error">error</span></li>
            <li><span class="t-warn">Warn</span> → <span class="t-neutral">any</span></li>
            <li><span class="t-error">Error</span> → <span class="t-normal">normal</span></li>
            <li><span class="t-error">Error</span> → <span class="t-warn">warn</span></li>
            <li><span class="t-error">Error</span> → <span class="t-neutral">any</span></li>
            <li><span class="t-neutral">Any</span> → <span class="t-normal">normal</span></li>
            <li><span class="t-neutral">Any</span> → <span class="t-warn">warn</span></li>
            <li><span class="t-neutral">Any</span> → <span class="t-error">error</span></li>
            <li><span class="t-neutral">Any</span> → <span class="t-neutral">any</span></li>
        </ol>
    </li>
    <li>
        <strong>Stay in range</strong> - how long to wait for a value to stay in a new range. A value may fluctuate but
        to avoid short peak values you can use this option. You can select not to wait and fire notifications
        immediately or wait a few minutes.
    </li>
    <li>
        <strong>Wait before firing again</strong> - you can select this if you want to fire this action several times
        when a value continuously stays in a new range or just fire once.
    </li>
    <li>
        <strong>Allow case to fire at any time</strong> - if it is turned on it will require other when cases to be
        fired on the same variable before this case can be fired again. It is useful in a scenario when a value jumps
        from a normal range to a warning or an error, stays there for a very short time and jumps back to a normal
        range. Notifications about being in the warning/error ranges is not triggered because with stay in range it is
        set to wait for longer timeframes. So the value jumped back to a normal range and if it is allowed to be fired
        at any time, it would fire the notification that the value is in the normal range again. Though it would be
        valid information it’s not necessarily needed since it was just a small value change in a short time.
    </li>
</ol>