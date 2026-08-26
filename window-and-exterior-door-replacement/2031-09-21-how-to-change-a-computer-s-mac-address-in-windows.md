---
title: "How to Change a Computer's MAC Address in Windows"
date: 2031-09-21 14:47
author: Noah Fitzgerald
---

# How to Change a Computer's MAC Address in Windows

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  QUIZZES All Quizzes Hot Love Quizzes  Personality Quizzes  Trivia Quizzes  Taylor Swift Quizzes  EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

Request a New ArticleCommunity DashboardTrendingForums

Arts and EntertainmentArtworkBooksMovies

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

[Address in Windows](https://address-in-windows.northlist.xyz/address-in-windows/20260826.html)

Personal Care and StyleFashionHair CarePersonal Hygiene

QuizzesLove QuizzesPersonality QuizzesFun Games

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

[How to Build an Outdoor Fort: 12 Steps (with Pictures) - wikiHow](https://github.com/ynx4vmkvha/yefuhl/blob/main/window-and-exterior-door-replacement/2030-12-13-how-to-build-an-outdoor-fort-12-steps-with-pictures-wikihow.md)

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account RANDOM Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Computers and Electronics Operating Systems Windows

[How to](https://how-to.themaplelane.com/how-to/20260826028.html)

3 Ways to Change a Computer's MAC Address in Windows Download Article

Changing your PC's MAC address with or without a program

Co-authored byHannah DillonReviewed byStan Kats

Last Updated: December 30, 2025Fact Checked Download Article Using Device Manager | Editing the Registry | Using Technitium | Video | Q&A | Warnings |Show more|Show less X

This article was reviewed by Stan Kats and by wikiHow staff writer, Hannah Dillon. Stan Kats is a Professional Technologist and the COO and Chief Technologist for The STG IT Consulting Group in West Hollywood, California. Stan provides comprehensive technology solutions to businesses through managed IT services, and for individuals through his consumer service business, Stan's Tech Garage. Stan holds a BA in International Relations from The University of Southern California. He began his career working in the Fortune 500 IT world. Stan founded his companies to offer an enterprise-level of expertise for small businesses and individuals. 

This article has been fact-checked, ensuring the accuracy of any cited facts and confirming the authority of its sources. 

This article has been viewed 1,401,232 times. 

There might be a time when you want to change the MAC address of your network adapter. The MAC address (Media Access Control address) is a unique identifier used to identify your computer within a network. Changing it can help you diagnose network issues, browse outside a school or your organization's allowed list of sites, or just have a little fun with a silly name. This wikiHow article teaches you how to change a computer's MAC address in Windows 10 and 11. Ways to Change Your PC's MAC Address

Use the Device Manager to change the properties of your network adapter.

[Change Computer's MAC](https://change-computer-s-mac.northlist.xyz/change-computer-s-mac/2026082612.html)

Use Registry Editor to change the MAC address registry.

Use a third-party program to easily change your MAC address. Steps Method 1 Method 1 of 3: Using Device Manager Download Article 1

Open Device Manager. To do this, right-click on the Windows button in your taskbar and click Device Manager. You can also search "device manager" in the taskbar search bar. 2

Expand the Network Adapters section. In your Device Manager, you will see a list of all of the hardware installed on your computer. These are sorted into categories. Expand the Network Adapters section to see all of your installed network adapters. Advertisement 3

[Change Computer's MAC](https://change-computer-s-mac.swapstreet.shop/change-computer-s-mac/2026082668.html)

Right-click on your adapter and select Properties. The network adapter's Properties window will open.

If you have a lot of options under the "network adapters" section, choose the one that ends with "network" or "ethernet connection." 4

Click the Advanced tab. You'll see this tab along the top of the window. 5

Select the "Network Address" or "Locally Administered Address" entry. The wording will depend on the type of network adapter you have.[1]XResearch source

Selecting it will reveal options on the right side of the window.

Not all adapters can be changed this way. If you can't find either of these entries, you need to use one of the other methods in this article. 6

[MAC Address in](https://mac-address-in.curblist.xyz/mac-address-in/20260826.html)

[Computer's MAC Address](https://computer-s-mac-address.swapstreet.shop/computer-s-mac-address/20260826.html)

Click the radio button to enable the "Value" field. 7

Enter your new MAC address. MAC addresses are 12-digit values and should be entered without any dashes or colons. For example, if you want to make the MAC address "2A:1B:4C:3D:6E:5F", you would enter "2A1B4C3D6E5F". 8

Reboot your computer to enable the changes. You can also disable and re-enable your adapter within Windows for the change to take effect without needing a reboot. Just sliding the Wi-Fi's On/Off switch like the slider found on ThinkPads and VaiOs won't satisfactorily disable/re-enable the card. 9

Check that the changes took effect. Once you've rebooted the computer, open the Command Prompt and enter ipconfig /all, and note the Physical Address of your adapter. It should be your new MAC address.[2]XResearch source Advertisement Method 2 Method 2 of 3: Editing the Registry Download Article 1

[to Change](https://to-change.swapstreet.shop/to-change/2026082682.html)

Find your network adapter's ID information. In order to easily identify your network adapter in the Windows Registry, you'll want to gather some basic information about it through the Command Prompt. You can open the Command Prompt by typing "cmd" into the Run box (Windows key + R).

Type ipconfig /all and press Enter. Note the Description and Physical Address for the active network device. Ignore devices that aren't active (Media Disconnected).[3]XResearch source

Type net config rdr and press ↵ Enter. Note the GUID, which is displayed between the "{ }" brackets next to the Physical Address you recorded earlier. 2

Open the Registry Editor. You can start the Registry Editor by opening the Run dialog box (Windows key + R) and typing "regedit". This will open the Registry Editor, which will allow you to change the settings for your network card.

Making incorrect changes to the registry can cause your system to malfunction. 3

Navigate to the registry key. Go to HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class{4D36E972-E325-11CE-BFC1-08002BE10318}. Expand it by clicking the arrow. 4

Find your adapter. There will be several folders labeled "0000", "0001", etc. Open each of these and compare the DriverDesc field to the Description you noted in the first step. To be completely sure, check the NetCfgInstanceID field and match it with the GUID from the first step.[4]XResearch source 5

Right-click on the folder that matches your device. For example, if the "0001" folder matches your device, right-click on the folder. Select New → String Value. Name the new value "NetworkAddress".[5]XResearch source 6

Double-click the new Network Address entry. In the "Value data" field, enter your new MAC address. MAC addresses are 12-digit values, and should be entered without any dashes or colons. For example, if you want to make the MAC address "2A:1B:4C:3D:6E:5F", you would enter "2A1B4C3D6E5F". 7

Ensure that the MAC address is formatted properly. Some adapters (especially Wi-Fi cards) are unforgiving of MAC address changes if the first octet's second half is not D2, D6, DA, or DE, or begins with a zero. This requirement has been observed as far back as Windows XP and is formatted as: D2XXXXXXXXXX D6XXXXXXXXXX DAXXXXXXXXXX DEXXXXXXXXXX 8

Reboot your computer to enable the changes. You can also disable and re-enable your adapter within Windows for the change to take effect without needing a reboot. 9

Check that the changes took effect. Once you've rebooted the computer, open the Command Prompt and enter ipconfig /all and note the Physical Address of your adapter. It should be your new MAC address.[6]XResearch source Advertisement Method 3 Method 3 of 3: Using Technitium Download Article 1

Go to technitium.com/tmac and download the software. Technitium is a third-party program, but it allows you to easily change your MAC address without having to edit anything you may not be comfortable with. 2

Open Technitium and select your network adapter. You'll see more details for your network adapter at the bottom of the window.[7]XResearch source 3

Enter a new MAC address under the "Change MAC address" field. If you don't see this, make sure the Information tab is active.[8]XResearch source

Click "Random MAC address" if you don't know one and the field will fill automatically. 4

Click Change Now!. You'll see this button become interactable once you enter a new MAC address.[9]XResearch source

You can easily return to your original MAC address by clicking the Restore Original button.[10]XResearch source Advertisement Community Q&A  Search Add New Question Question

How do I know which MAC addrress can I use and is it safe ? Should I do a system backup ? Community Answer

There are many MAC addresses in the world, so the chances of having the same one on the same network are slim. Don't worry about it unless you have changed two devices to that MAC address. You don't have to do a backup because it's something that will reset if you delete the entry and then restart your computer.  Thanks! We're glad this was helpful. Thank you for your feedback.

[to Change Computer's MAC](https://to-change-computer-s-mac.northlist.shop/to-change-computer-s-mac/20260826922.html)

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 15Helpful 33 Question

If I change this MAC address, will it change the MAC address on my iPad and iPhone? Allan Cramer Community Answer

No, the MAC address is unique to each device. I'm not even sure you can change Apple MAC addresses, but if you can, you'll have to do that with each one.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 6Helpful 21 Question

If I delete the new registry entry I create, will the original Mac address be used again? Community Answer

No, the Mac address that you set is permanent and you'll have to do a hard reset to get the original address back.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 44Helpful 10 See more answers Ask a Question 200 characters left

Include your email address to get a message when this question is answered. Submit Advertisement Video Tips Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  Warnings

Don't use a MAC address that is already in use, as this will prevent one of the machines from connecting to the network. Thanks Helpful 1 Not Helpful 0 Advertisement You Might Also Like

4 Quick Ways to Find the MAC Address on Your Windows 11 PC How to Find the MAC Address of Your Computer How to Change MAC Address on Ubuntu How to Change a Mac Address on an Android 8 Easy Ways to Change Your IP Address How to

Change or Reset Your Public or Private IP Address How to

Find Your Subnet Mask: The Complete Guide

4 Easy Ways to Manually Reset the Wi-Fi Adapter in Windows

A Step-By-Step Guide to Aquire a New IP Address How to

Get a MAC Address from an IP Address on PC, Mac, & Linux

3 Quick Ways to Change Your Windows 10 PC Name + Fixes How to

Set Up MAC Address Filtering on Any Wireless Router Advertisement References

↑https://learn.microsoft.com/en-us/answers/questions/711131/changing-mac-address-without-using-third-party-app

[Change Computer's MAC](https://change-computer-s-mac.northlist.xyz/change-computer-s-mac/2026082644.html)

↑https://www.geeksforgeeks.org/how-to-modify-mac-address-in-windows-10-both-wired-and-wireless-adapter/#

↑https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ipconfig

↑https://techjourney.net/how-to-change-or-spoof-mac-address-in-windows-windows-server-macos-unix-linux/

↑https://techjourney.net/how-to-change-or-spoof-mac-address-in-windows-windows-server-macos-unix-linux/

↑https://techjourney.net/how-to-change-or-spoof-mac-address-in-windows-windows-server-macos-unix-linux/ ↑https://technitium.com/tmac/help.html ↑https://technitium.com/tmac/ ↑https://technitium.com/tmac/help.html More References (1) ↑https://technitium.com/tmac/ About This Article Reviewed by:  Stan Kats Professional Technologist

This article was reviewed by Stan Kats and by wikiHow staff writer, Hannah Dillon. Stan Kats is a Professional Technologist and the COO and Chief Technologist for The STG IT Consulting Group in West Hollywood, California. Stan provides comprehensive technology solutions to businesses through managed IT services, and for individuals through his consumer service business, Stan's Tech Garage. Stan holds a BA in International Relations from The University of Southern California. He began his career working in the Fortune 500 IT world. Stan founded his companies to offer an enterprise-level of expertise for small businesses and individuals. This article has been viewed 1,401,232 times.  How helpful is this? Co-authors: 29 Updated: December 30, 2025 Views: 1,401,232

Categories: Windows | Computer Networking In other languages Spanish Italian German Russian Chinese French Dutch Indonesian Arabic Czech Thai Vietnamese Korean Japanese Print Send fan mail to authors

Thanks to all authors for creating a page that has been read 1,401,232 times. Reader Success Stories Anonymous Aug 31, 2017 "Article was really helpful."  Rated this article: More reader storiesHide reader stories Share your story Is this article up to date? YesNo Advertisement

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. Reviewed by:  Stan Kats Professional Technologist Click a star to vote Co-authors: 29 Updated: December 30, 2025 Views: 1,401,232 Anonymous Aug 31, 2017 "Article was really helpful."  Rated this article: Zahra S. Oct 22, 2016 "Perfect, thank you so much!" 

Share yours!More success storiesHide success stories Quizzes & Games Discord Username Idea Generator Generate Names Gamertag Generator Generate Names Snapchat Username Generator Generate Names Random Name Generator Generate Names You Might Also Like

4 Quick Ways to Find the MAC Address on Your Windows 11 PC How to Find the MAC Address of Your Computer How to Change MAC Address on Ubuntu How to Change a Mac Address on an Android Trending Articles Am I Chopped Quiz Can We Guess How Tall You Are Quiz Kiss, Marry, Kill Quiz What’s the Name of My Crush? Trending Articles Finish the Lyrics TikTok Edition

Design a Morning Routine and Learn Your Superpower

Pick a Door and We'll Reveal What You're Missing What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos

The Right Way to Refrigerate and Freeze Fresh Green Beans

A Complete Guide to Shaving Your Body (and Preventing Razor Burn) How to

Play "What Are the Odds?" (Also Known As "Odds Are")

4 Easy Ways to Draw Cute and Realistic Cats Hot Takes Only 🔥 Overrated or Underrated Game

Do You Agree With These Spicy Hot Takes?

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose? Your Daily Dose of Fun 🎉

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Rizz Game: Test Your Rizz

Can You Pull Off The Perfect Heist? Prove Yourself Categories Computers and Electronics Operating Systems Windows

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Newsletter You're all set! Helpful how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us ×

Keep up with the latest tech with wikiHow's free Tech Help Newsletter Subscribe You're all set! X - - 669
