---
layout: post
title:  "How the display types string, number, base and percent are different?"
uri: how-the-display-types-string-number-base-and-percent-are-different
tags: [data sources]
---

<p>
    <strong>Display type string</strong> is used to display string values. While it’s not a number, it has no value
    range or extra display options. It’s the most basic display type - just show the value as it is in the output of the
    command.
</p>

<!--more-->
<!-- todo add img -->

<p>
    <strong>Display type number</strong> is used to display any number. As all numeric types, it has value range options
    to set when a value is in a warning or error ranges. Also. you can set how many decimal places to show.
</p>
<!-- todo add img -->

<p>
    <strong>Display type base</strong> is used to display numeric values that has to be divided by base, rounded and
    have the suffix of letters. As all numeric types, it has value range options to set when the value is in the warning
    or error ranges.
</p>
<p>
    It is a very useful display type for sizes, e.g. a command output is in bytes and you want to see
    Megabytes. After the default installation of Trafikito agent you can see this type in use with disk space usage data
    source.
</p>
<!-- todo add img -->

<p>
    <strong>Display type percent</strong> is used to display percentage representation of the number. As all numeric
    types, it has value range options to set when value is in warning or error ranges. You can also define how many
    decimal places to use and what is minimum and maximum values for this number.
</p>
<!-- todo add img -->

