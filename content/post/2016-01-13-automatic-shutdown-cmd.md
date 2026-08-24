---
id: 978
title: 'Automatic Timed Shutdown with Command Prompt (CMD)'
date: '2016-01-13T23:30:33+05:30'
author: 'Swapnil Jha'
excerpt: 'Today, we will discuss how to trigger an automatic shutdown to any computer.'
layout: post
guid: 'http://techglobule.com/?p=978'
permalink: '/2016/01/automatic-shutdown-cmd/'
apple_news_api_id:
    - d4e987e5-bbab-4e83-845e-8c8b5e967212
apple_news_api_created_at:
    - '2017-01-30T18:05:18Z'
apple_news_api_modified_at:
    - '2017-01-30T18:05:18Z'
apple_news_api_share_url:
    - 'https://apple.news/A1OmH5burToOEXoyLXpZyEg'
apple_news_api_revision:
    - AAAAAAAAAAD//////////w==
categories:
    - 'Windows OS'
tags:
    - 'Windows 10'
    - 'Windows 7'
    - 'Windows 8'
format: false
wp_id: '978'
---

<h1 style="text-align: center;">Hi Guys,</h1>
<p style="text-align: justify;">It happens a lot, that we need someone else' assistance to shut down our computers, in case we have to leave urgently, but we won't need that assistance anymore.</p>
<h2 style="text-align: center;">Why can I need Automatic Shutdown for?</h2>
<p style="text-align: justify;">There can be infinitely many scenarios where you might need to shut down your computer after a certain period of time, for example -</p>
<ul style="text-align: justify;">
    <li>While waiting for a download to complete.</li>
    <li>While waiting for a long antivirus scan.</li>
    <li>While waiting for any thing which is gonna take a predictable amount of time.</li>
    <li>Or maybe playing a cruel prank on a friend <a class="emoji" title="U+1F60F" href="http://apps.timwhitlock.info/emoji/tables/unicode#emoji-modal"><span class="emoji">?</span></a><a class="emoji" title="U+1F60F" href="http://apps.timwhitlock.info/emoji/tables/unicode#emoji-modal"><span class="emoji">?</span></a></li>
</ul>
<p style="text-align: justify;">For any such event, we can just set the timer 10-15 minutes more than their estimated time of completion and just go on with your other work.</p>
<h2 style="text-align: center;">What is Command Prompt aka CMD?</h2>
<p style="text-align: justify;">A command prompt is an entry point for typing commands to the computer. By typing commands at the command prompt, you can perform tasks on your computer without using the Windows graphical interface.</p>
<p style="text-align: justify;">You can do almost all the things with CMD, which you can do with the Operating System, sometimes even more.</p>
<h2 style="text-align: center;">How to trigger an automatic shutdown?</h2>
<p style="text-align: justify;">Follow these steps -</p>
<ul style="text-align: justify;">
    <li>Press Windows button + R, to get to Run.</li>
    <li>The commands can be directly entered here.</li>
    <li>The command to shut down is <strong>shutdown -s</strong></li>
    <li>This command will shutdown your computer in 1 minute. You will get this message.[gallery type="rectangular" size="medium" ids="1596,1595,1594"]
&nbsp;</li>
</ul>
<h2 style="text-align: center;">How to set a time period and other functionalities?</h2>
<h3 style="text-align: justify;">Command to automatic shutdown -</h3>
<p style="text-align: justify;">shutdown -s</p>
<h3 style="text-align: justify;">Command to cancel shutdown -</h3>
<p style="text-align: justify;">shutdown -a</p>
<h3 style="text-align: justify;">Command to schedule shutdown after 5 min (300 seconds) -</h3>
<p style="text-align: justify;">shutdown -s -t 300
One can set any amount of time in seconds format, like for 10 minutes, command will be shutdown -s -t 600</p>
<h3 style="text-align: justify;">Command to add a custom message "LOL :)" with shutdown -</h3>
<p style="text-align: justify;">shutdown -s -c "LOL :)"
One can set any custom message, like "Revenged", command will be shutdown -s -c "Revenged"</p>
<h3 style="text-align: justify;">Command to restart computer -</h3>
<p style="text-align: justify;">shutdown -r</p>
<h3 style="text-align: justify;">Note -</h3>
<p style="text-align: justify;">One can use several of these commands in a single command. For example, commands like the one below will work.</p>
<p style="text-align: justify;">shutdown -r -t 3600 -c "I took my revenge."</p>
<h1 style="text-align: center;">That's all folks.</h1>
<h6 style="text-align: justify;">Image Source - thedailybuggle.com (Featured image) and Swapnil's Compaq Laptop (for other screenshots).
Data source - codechewing.com.
Author - Swapnil Jha</h6>
