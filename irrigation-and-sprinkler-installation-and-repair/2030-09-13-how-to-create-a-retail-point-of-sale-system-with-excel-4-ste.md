---
title: "How to Create a Retail Point‐of‐Sale System with Excel: 4 Steps"
date: 2030-09-13 15:00
author: Gabriel Silva
---

# How to Create a Retail Point‐of‐Sale System with Excel: 4 Steps

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  QUIZZES All Quizzes Hot Love Quizzes  Personality Quizzes  Trivia Quizzes  Taylor Swift Quizzes  EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

Request a New ArticleCommunity DashboardTrendingForums

Arts and EntertainmentArtworkBooksMovies

[with Excel](https://with-excel.curblist.xyz/with-excel/202608266629.html)

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

Personal Care and StyleFashionHair CarePersonal Hygiene

QuizzesLove QuizzesPersonality QuizzesFun Games

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account RANDOM Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Work World Occupations Sales Occupations Retail Sales Skills

How to Create a Retail Point‐of‐Sale System with Excel Download Article Explore this Article Steps Steps   Other Sections Questions & Answers   Video   Tips and Warnings   Related Articles   Co-authored byLuigi Oppido Last Updated: May 30, 2024 Download Article X

This article was co-authored by Luigi Oppido. Luigi Oppido is the Owner and Operator of Pleasure Point Computers in Santa Cruz, California. Luigi has over 25 years of experience in general computer repair, data recovery, virus removal, and upgrades. He is also the host of the Computer Man Show! broadcasted on KSQD covering central California for over 7 years. 

This article has been viewed 208,208 times. 

Do you need a simple POS (point of sale) system for your small retail shop? With this method, you can manage the following facilities without special software or expensive equipment: Issue a sales bill using barcode Manage purchases Control inventory Day end and month end stock balance Daily sales Daily purchases Steps Download Article 1

Learn Microsoft Excel. Learn about Excel macros.

Create Excel workbook with 6 worksheets for followings steps like this: Bills Pur Purchase Sales Stock balance Setup 2

Create a setup page with these headings, setup your stock items

Category Code : Create specific codes for your each item. This must be a unique ID number for each items. Use this to create the barcodes.

[Retail Point of](https://retail-point-of.curblist.xyz/retail-point-of/20260826.html)

[to Create Retail](https://to-create-retail.northlist.xyz/to-create-retail/2026082608.html)

According to this, take all the inventory items & create a code and update the sheet with opening stock, pur, price, and sales price. You have to give the correct purchase price and sales prices because when you issue a bill, price will be selected from this sheet. The opening balance will be linked with the stock balance sheet. If you don’t have a barcode printer, just print the receipt to A4 Sheet and paste it to your sales items. Create a Stock balance sheet: Create this sheet with below headings:

Copy this formula to each row and copy paste to down:

Code: =IF(setup!$B$3:$B$323"",setup!$B$3:$B$323,"")

Description: =IF(setup!$C$3:$C$323"",setup!$C$3:$C$323,"")

Opening Balance: =SUM(IF(B3=setup!$B$3:$B$1021,setup!$D$3:$D$1021))

Purchase: =SUM(IF(B3=purchase!$B$2:$B$2005,purchase!$D$2:$D$2005))

Sales: =SUM(IF(B3=sales!$H$2:$H$2551,sales!$J$2:$J$2551)) Stock: =+D3+E3-F3 Advertisement 3 Create a bill sheet:

Create a sheet according to this format and give the below formula to each row and create macros with below codes. Line: =IF(C5="","",B4+1)

Code: Create a list box link with setup page item code and name. when you connect a bar code reader with bar code sticker details will auto pick. Description: =I4

Qty : this column you have to enter manually according to customer purchase qty.

Price: =IF(E4="","",VLOOKUP(C4,al,5,0)*E4) macro for Save bill

Create a button called Save bill and copy this code: You can download this file form file Sub Dayendsales()' 'Dayendsales Macro Sheets("Tsales").Select Columns("G:G").Select

Selection.Insert Shift:=xlToRight, CopyOrigin:=xlFormatFromLeftOrAbove Range("E2:E255").Select Selection.copy Range("G2").Select

Selection.PasteSpecial Paste:=xlPasteValues, Operation:=xlNone, SkipBlanks _ =False, Transpose:=False Sheets("sales").Select Range("B3:D1572").Select Application.CutCopyMode = False Selection.ClearContents Range("D3").Select End Sub Sub DayendPurchases()' ' DayendPurchases Macro' Sheets("Tpurchase").Select Columns("F:F").Select

Selection.Insert Shift:=xlToRight, CopyOrigin:=xlFormatFromLeftOrAbove Range("D2:D643").Select Selection.copy Range("F2").Select

[Best Times on Post on TikTok in 2026: A Complete Guide](https://github.com/uu4du0j9lu/jvloubd/blob/main/post-construction-cleaning/2031-08-06-best-times-on-post-on-tiktok-in-2026-a-complete-guide.md)

Selection.PasteSpecial Paste:=xlPasteValues, Operation:=xlNone, SkipBlanks _ =False, Transpose:=False Application.CutCopyMode = False Sheets("purchase").Select Range("C3:D625").Select Selection.ClearContents Range("E3").Select End Sub Sub SaveBill()' ' SaveBill Macro'

Application.Run "'shop sales control.xls'!copy"

Application.Run "'shop sales control.xls'!SaleReplace" End Sub Sub DayEnd()' ' DayEnd Macro End Sub 4

Create a Pur sheet: according to this format

Now create the Purchase and sales data save page with this format: Sales data base Advertisement Community Q&A  Search Add New Question Question

How does this work with a scanner and bar codes? Community Answer

A scanner replicates keyboard entry. Instead of entering all the barcode digits on the keyboard, the scanner reads them and enters them for you.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 4Helpful 25 Ask a Question 200 characters left

[of Sale](https://of-sale.themaplelane.com/of-sale/20260826628.html)

Include your email address to get a message when this question is answered. Submit Advertisement Video Tips Create Bar code: Thanks Helpful 1 Not Helpful 5

Download Bar code Generator or can do it Online. Thanks Helpful 0 Not Helpful 1

Example for barcode I generate for sample file Thanks Helpful 0 Not Helpful 0 Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  Advertisement You Might Also Like How to Track your Bills in Microsoft Excel How to Create a Barcode How to Create a Budget Spreadsheet How to

Create an Inventory List in Microsoft Excel: Step-by-Step Guide How to Make a Spreadsheet in Excel How to Write a Receipt How to

Create a Break Even Chart in Excel for Your Business Expenses How to Automate Reports in Excel How to

Create a Simple Checkbook Register With Microsoft Excel How to Use a Cash Register How to

Create a Calendar in Microsoft Excel: 3 Easy Methods

Excel Macros: How to Run, Record, and Use Macros in Excel Advertisement About This Article Co-authored by:  Luigi Oppido Computer & Tech Specialist

This article was co-authored by Luigi Oppido. Luigi Oppido is the Owner and Operator of Pleasure Point Computers in Santa Cruz, California. Luigi has over 25 years of experience in general computer repair, data recovery, virus removal, and upgrades. He is also the host of the Computer Man Show! broadcasted on KSQD covering central California for over 7 years. This article has been viewed 208,208 times.  474 votes - 69% Co-authors: 22 Updated: May 30, 2024 Views: 208,208 Categories: Retail Sales Skills In other languages Japanese Print Send fan mail to authors

Thanks to all authors for creating a page that has been read 208,208 times. Did this article help you? YesNo Advertisement

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. Co-authored by:  Luigi Oppido Computer & Tech Specialist 474 votes - 69% Click a star to vote Co-authors: 22 Updated: May 30, 2024 Views: 208,208 Quizzes & Games Grocery Store Simulator Play Memory Test Take Quiz What Wholesale Items Should I Sell Quiz Take Quiz What Age Is My Brain Quiz Take Quiz You Might Also Like How to Track your Bills in Microsoft Excel How to Create a Barcode How to Create a Budget Spreadsheet How to

Create an Inventory List in Microsoft Excel: Step-by-Step Guide Trending Articles Am I Chopped Quiz Can We Guess How Tall You Are Quiz Kiss, Marry, Kill Quiz What’s the Name of My Crush? Trending Articles Finish the Lyrics TikTok Edition

Design a Morning Routine and Learn Your Superpower

Pick a Door and We'll Reveal What You're Missing What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos

[System with Excel Steps](https://system-with-excel-steps.swapstreet.shop/system-with-excel-steps/202608269116.html)

The Right Way to Refrigerate and Freeze Fresh Green Beans

A Complete Guide to Shaving Your Body (and Preventing Razor Burn) How to

Play "What Are the Odds?" (Also Known As "Odds Are")

[to Create](https://to-create.themaplelane.com/to-create/20260826.html)

4 Easy Ways to Draw Cute and Realistic Cats Hot Takes Only 🔥 Overrated or Underrated Game

Do You Agree With These Spicy Hot Takes?

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose? Your Daily Dose of Fun 🎉

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Rizz Game: Test Your Rizz

Can You Pull Off The Perfect Heist? Prove Yourself Categories Work World Occupations Sales Occupations Retail Sales Skills

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Newsletter You're all set! Helpful how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us × Get all the best how-tos!

Sign up for wikiHow's weekly email newsletter Subscribe You're all set! X - - 704
