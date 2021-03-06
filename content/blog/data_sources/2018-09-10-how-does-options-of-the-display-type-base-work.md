---
layout: post
title:  "How does options of the display type: base work?"
uri: how-does-options-of-the-display-type-base-work
tags: [data sources]
---

<p>
    Display type base can be used with numeric values. It can do some basic math and apply suffix to the final number.
    This is how it works:
</p>

<!--more-->

<p>
    Let’s say we use <span class="t-code">df -P</span> command to get the available disk space and the current value is
    <strong>3977700</strong>. It means there are <strong>3977700 Kilobytes</strong> left. It is useful to have the raw
    value to display it on a chart but on a text box it would be better to have a formatted value.
</p>
<p>
    You can set Base as <strong>1024</strong> and add a few names. We will use <span class="t-code">KB</span>, <span
        class="t-code">MB</span>, <span class="t-code">GB</span> and <span class="t-code">TB</span> for now. Trafikito
    will take the raw value of <strong>3977700</strong> and divide it by <strong>1024</strong>:
</p>
<div class="t-code">3977700 / 1024 = 3884.47265625</div>
<br>
<p>
    While <strong>3884</strong> is more then <strong>1024</strong>, it will be divided again:
</p>
<div class="t-code">3884.47265625 / 1024 = 3.7934303284</div>
<br>

<p>
    Now you have decimal places option - how many numbers to show in decimal places. If it is set to <strong>2</strong>,
    final formatted value will be <strong>3.79</strong> and while it was divided <strong>2</strong> times, the 3rd value
    name will be used, which in our case is <span class="t-code">GB</span>. So the final render with suffix is: <span
        class="t-code">3.79 GB</span>
</p>