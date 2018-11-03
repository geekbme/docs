---
title: Oculus: Recreating the Demo
description: Your Guide to Recreating Elements of the Oculus Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/oculus:Oculus

---

Introduction
-----

![][oculus]

Recreating features of the demo site used to show off some of the more interesting aspects of Oculus can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Oculus Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----


Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][oculus2]

:   1. **Header Login**  [8%, 83%, sw]
    2. **RokAjaxSearch**  [11%, 69%, se]
    3. **FP RokSprocket Features - Slideshow**  [14%, 15%, se]
    4. **FP Showcase A**  [29%, 15%, se]
    5. **Most Popular**  [14%, 86%, sw]
    6. **Popular News**  [34%, 45%, se]
    7. **Popular Features**  [55%, 45%, se]
    8. **Gantry Extras**  [34%, 86%, sw]
    9. **Oculus Demo**  [51%, 86%, sw]
    10. **Our Users** [66%, 86%, sw]
    11. **FP Footer A**  [78%, 15%, se]
    12. **Inside Oculus** [78%, 35%, se]
    13. **Top Features** [78%, 53%, se]
    14. **Contact Us** [78%, 70%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [Header Login][module1]
2. [RokAjaxSearch][module2]
3. [FP RokSprocket Features - Slideshow][module3]
4. [FP Showcase A][module4]
5. [Most Popular][module5]
6. [Popular News][module6]
7. [Popular Features][module7]
8. [Gantry Extras][module9]
9. [Oculus Demo][module10]
10. [Our Users][module11]
11. [FP Footer A][module12]
12. [Inside Oculus][module13]
13. [Top Features][module14]
14. [Contact Us][module15]


Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Oculus:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](https://rockettheme.com/joomla/extensions/rokutilities)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]
* [RokPad][rokpad]
* [RokBooster][rokbooster]

Many of these extensions are included with the Oculus RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Oculus demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Oculus template.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Oculus - Home** as it would be used only for the front page of your site.

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

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to `-jun13-home`.

You can also set the Dropdown Menu Offset in order to center the sub-menu as seen in our demo. As an example, we will look at the settings for the Features sub-menu within the **Main Menu** found at the top of the **Home** page.

[gantry]: http://gantry.org/downloads
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[Oculus2]: assets/oculus2.jpeg
[oculus]: assets/oculus.jpeg
[demooverride]: demo_override.md
[roknavmenu]: http://www.rockettheme.com/joomla/extensions/roknavmenu
[rokbooster]: http://www.rockettheme.com/joomla/extensions/rokbooster
[rokcandy]: http://www.rockettheme.com/joomla/extensions/rokcandy
[rokpad]: http://www.rockettheme.com/joomla/extensions/rokpad
[rokbooster]: http://www.rockettheme.com/joomla/extensions/rokbooster
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
[mainmenu]: menu_1.jpg
[login]: a_header_login.jpg