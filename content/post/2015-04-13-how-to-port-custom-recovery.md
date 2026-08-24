---
id: 410
title: 'How to Port Custom Recovery?'
date: '2015-04-13T20:22:38+05:30'
author: Siddhant
excerpt: 'Hi Guys, today we will discuss about porting custom recovery.'
layout: post
guid: 'http://techglobule.com/?p=410'
permalink: '/2015/04/how-to-port-custom-recovery/'
apple_news_api_id:
    - 655194da-62a7-4d28-95a3-b7722dadf1a5
apple_news_api_created_at:
    - '2017-01-30T18:15:06Z'
apple_news_api_modified_at:
    - '2017-01-30T18:15:07Z'
apple_news_api_share_url:
    - 'https://apple.news/AZVGU2mKnTSiVo7dyLa3xpQ'
apple_news_api_revision:
    - AAAAAAAAAAD//////////w==
categories:
    - 'Android Rooting'
tags:
    - CyanogenMod
    - Rooting
format: false
wp_id: '410'
---

<h1 style="text-align: center;">Hi Guys,</h1>
<p style="text-align: justify;">Today we are gonna discuss about how to port Custom recoveries in an Android device. So, let's start.</p>
<h2 style="text-align: center;">What is a custom recovery?</h2>
A custom recovery is a third-party recovery tool environment. Flashing (aka installing) this recovery environment onto your device replaces the default stock recovery environment. This is a bit like flashing a <a href="/category/android/custom-roms/" target="_blank" rel="noopener noreferrer">Custom ROM</a>s like <a title="CyanogenMod: An Introduction" href="/2015/04/cm/" target="_blank" rel="noopener noreferrer">CyanogenMod</a> — but, instead of replacing your device’s Android operating system, it replaces the recovery environment.
<h2 style="text-align: center;">Why to install a custom recovery?</h2>
A custom recovery environment will do the same things as the stock Android recovery. However, it will also have additional features. Custom recoveries also have the ability to create and restore device backups. Custom recoveries allow you to install <a href="/category/custom-roms/" target="_blank" rel="noopener noreferrer">Custom ROMs</a>. ClockworkMod even offers a “<a href="https://play.google.com/store/apps/details?id=com.koushikdutta.rommanager&amp;hl=en" target="_blank" rel="noopener noreferrer">ROM Manager</a>” app that allows you to access many of these features from a running Android system — this app requires a custom recovery installed to function properly.
<h2 style="text-align: center;">How to port custom recovery?</h2>
<p style="text-align: justify;">First of all your Android device should be rooted to do this. To know if your device is rooted or not, download <a href="https://play.google.com/store/apps/details?id=com.joeykrim.rootcheck&amp;hl=en" target="_blank" rel="noopener noreferrer">Root Checker</a> from the Google Play Store. To root your android device, you may prefer the <a href="/2015/03/ways-of-rooting/" target="_blank" rel="noopener noreferrer">Ways of Rooting</a> post.</p>
<ul>
	<li style="text-align: left;">Download <a href="http://twrp.me/" target="_blank" rel="noopener noreferrer">TWRP</a>/<a href="http://www.xda-developers.com/cannibal-open-touch-recovery/" target="_blank" rel="noopener noreferrer">COT</a>/<a href="http://forum.xda-developers.com/showthread.php?t=2201860" target="_blank" rel="noopener noreferrer">PhilZ</a> or <a href="https://www.clockworkmod.com/" target="_blank" rel="noopener noreferrer">CWM</a> on your PC from any <strong>Mediatek</strong> device with same screen resolutions.</li>
	<li style="text-align: left;">Make sure you have your stock recovery. You can get it with a ReadBack or <a href="http://forum.xda-developers.com/attachment.php?s=27da62aab5e6b6c8c737717b154e8ad8&amp;attachmentid=3172884&amp;d=1424322722" target="_blank" rel="noopener noreferrer">MTK Droid Root and Tools backup</a>.</li>
	<li style="text-align: left;">Now download MTK Boot/Recovery image unpack tool from here.</li>
	<li style="text-align: left;">Extract this tool in one folder.</li>
	<li style="text-align: left;">Put the images [carliv recovery and stock] in that folder which has extracted tools.</li>
	<li style="text-align: left;">Now drag and drop stock recovery to MTK_unpack.bat file.</li>
	<li style="text-align: left;">Same with the case of Custom Recovery.</li>
	<li style="text-align: left;">Now open the folder of stock recovery folder and open a folder rmdsk in it.</li>
	<li style="text-align: left;">Copy these files:
meta_init.project.rc
meta_init.rc
ueventd.rc
meta_init.modem.rc
ueventd.goldfish.rc
fstab</li>
	<li style="text-align: left;">Open etc folder and copy recovery.fstab file too.</li>
	<li style="text-align: left;">Now replace these files in the Custom recovery with the same directories.</li>
	<li style="text-align: left;">Now go back and copy these files from the main folder in which you have your stock recovery's extracted rmdsk and kernel files:
kernel
kernel_header</li>
	<li style="text-align: left;">Replace these files in the Custom Recovery too.</li>
	<li style="text-align: left;">Now go back to the main folder where you extracted the tool and .IMGs files.</li>
	<li style="text-align: left;">Drag and drop the CTR folder to MTK_pack.bat file.</li>
	<li style="text-align: left;">You're done! Now try flashing!</li>
</ul>
<h1 style="text-align: center;">That's all folks.</h1>
Image source - theandroidsoul.com
Author - Siddhant Baranwal
Co - Author - Swapnil Jha &amp; Abdul Rehman
