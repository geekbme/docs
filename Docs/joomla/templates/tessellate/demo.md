---
title: Tessellate: Recreating the Demo
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Tessellate can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Tessellate Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][template2]

:   1. **RokAjaxSearch**  [5%, 29%, se]
    2. **FP RokSprocket Features**  [6%, 84%, sw]
    3. **Custom HTML - FP Top A**  [12%, 21%, se]
    4. **Custom HTML - About Tessellate**  [15%, 17%, se]
    5. **Custom HTML - FP Showcase B**  [15%, 41%, se]
    6. **Custom HTML - FP Showcase C**  [15%, 58%, se]
    7. **RokSprocket Tabs - Showcase**  [21%, 62%, se]
    8. **Custom HTML - FP Feature A**  [28%, 17%, se]
    9. **Custom HTML - Powered by LESS CSS**  [29%, 64%, se]
    10. **Custom HTML - RokAjaxSearch**  [36%, 64%, se]
    11. **Custom HTML - Using Tessellate**  [42%, 17%, se]
    12. **Custom HTML - RocketLauncher Packages** [48%, 17%, se]
    13. **Custom HTML - Free Online Documentation** [48%, 51%, se]
    14. **Custom HTML - FP MainTop A** [52%, 17%, se]
    15. **Custom HTML - FP Maintop B** [52%, 51%, se]
    16. **Featured Article** [62%, 17%, se]
    17. **RokSprocket Tabs - MainBottom** [68%, 17%, se]
    18. **RokSprocket Strips - Multiple Layouts** [75%, 17%, se]
    19. **Custom HTML - Disclaimer** [85%, 17%, se]
    20. **Custom HTML - Info** [85%, 40%, se]
    21. **Custom HTML - Pages** [85%, 52%, se]
    22. **Custom HTML - Newsletter** [85%, 64%, se]
    23. **Menu - FP Copyright Menu** [92%, 72%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [RokAjaxSearch][module1]
2. [FP RokSprocket Features][module2]
3. [Custom HTML - FP Top A][module3]
4. [Custom HTML - About Tessellate][module4]
5. [Custom HTML - FP Showcase B][module5]
6. [Custom HTML - FP Showcase C][module6]
7. [RokSprocket Tabs - Showcase][module7]
8. [Custom HTML - FP Feature A][module8]
9. [Custom HTML - Powered by LESS CSS][module9]
10. [Custom HTML - RokAjaxSearch][module10]
11. [Custom HTML - Using Tessellate][module11]
12. [Custom HTML - RocketLauncher Packages][module22]
13. [Custom HTML - Free Online Documentation][module23]
14. [Custom HTML - FP MainTop A][module12]
15. [Custom HTML - FP Maintop B][module13]
16. [Featured Article][module14]
17. [RokSprocket Tabs - MainBottom][module15]
18. [RokSprocket Strips - Multiple Layouts][module16]
19. [Custom HTML - Disclaimer][module17]
20. [Custom HTML - Info][module18]
21. [Custom HTML - Pages][module19]
22. [Custom HTML - Newsletter][module20]
23. [Menu - FP Copyright Menu][module21]


Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Tessellate:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](https://rockettheme.com/joomla/extensions/rokutilities)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Tessellate RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Tessellate demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Tessellate demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Tessellate - Home** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. 

You will need to start by navigating to **Admin > Extensions > Template Manager > (Your Home Override)** and select the **Assignments** tab. Under the **Main Menu** list, you will want to select **Home**.

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You can find these settings by navigating to **Admin > Menus > Main Menu > Home**. Once there, you will want to select the **Page Display** tab.

You will need to change the **Page Class** setting under the Home menu item to ` aug14-home`.

[gantry]: http://gantry.org/downloads
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[template2]: assets/tessellate2.jpg
[demooverride]: demo_override.md
[roknavmenu]: http://www.rockettheme.com/joomla/extensions/roknavmenu
[rokbooster]: http://www.rockettheme.com/joomla/extensions/rokbooster
[rokcandy]: http://www.rockettheme.com/joomla/extensions/rokcandy
[module1]: demo_module_1.md
[module2]: demo_module_2.md
[module3]: demo_module_3.md
[module4]: demo_module_4.md
[module5]: demo_module_5.md
[module6]: demo_module_6.md
[module7]: demo_module_7.md
[module8]: demo_module_8.md
[module9]: demo_module_9.md
[module10]: demo_module_10.md
[module11]: demo_module_11.md
[module12]: demo_module_12.md
[module13]: demo_module_13.md
[module14]: demo_module_14.md
[module15]: demo_module_15.md
[module16]: demo_module_16.md
[module17]: demo_module_17.md
[module18]: demo_module_18.md
[module19]: demo_module_19.md
[module20]: demo_module_20.md
[module21]: demo_module_21.md
[module22]: demo_module_22.md
[module23]: demo_module_23.md
[mainmenu]: assets/menu_1.jpeg
[article]: assets/article.jpg
[demo11]: assets/demo_10.jpeg
[mobile]: assets/mobilemenu.jpeg
[mobile2]: mobilemenu.md
[sidepanelmodule]: demo_module_10.md
[sidepanel]: assets/sidepanel.jpeg
