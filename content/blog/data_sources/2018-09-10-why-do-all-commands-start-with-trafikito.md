---
layout: post
title:  "Why do all commands start with trafikito_?"
uri: why-do-all-commands-start-with-trafikito
tags: [data sources]
---

<p>
    For higher security standards. By using only alias commands on your server Trafikito ensures that no unexpected
    commands run. Imagine losing your login details or having an angry person on your team with an admin role.
</p>

<!--more-->

<p>
    Without prefix restrictions, someone with bad intentions may add <span class="t-code">rm -rf /</span> (remove
    everything from the server) or similar damaging commands and without protection, Trafikito would run it.
</p>

<p>
    Utilizing <strong>trafikito_</strong> prefix guarantees that Trafikito agent only uses commands that are aliases for
    something. You explicitly have to login to your machine in order to edit <span
        class="t-code">/opt/trafikito/available_commands.sh</span> file to have a new command available.
</p>

<p>
    By default, during installation, Trafikito adds aliases for all of the most popular commands such as <span
        class="t-code">uptime</span>, <span class="t-code">free</span> or <span class="t-code">df</span>. So, you
    can just select those from the drop-down when adding new data sources.
</p>