---
title: Metropolis: Recreating the Demo
description: Your Guide to Recreating Elements of the Metropolis Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/metropolis:Metropolis

---

Introduction
-----

![][Metropolis2]

Recreating features of the demo site used to show off some of the more interesting aspects of Metropolis can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Metropolis Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----


Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][Metropolis]

:   1. **FP Showcase - RokSprocket Features**  [11%, 11%, se]
    2. **FP Feature - RokSprocket Mosaic**  [25%, 11%, se]
    3. **About Metropolis**  [45%, 11%, se]
    4. **From Blog**  [55%, 11%, se]
    5. **Help & Tips**  [45%, 52%, se]
    6. **Our Users**  [58%, 52%, se]
    7. **Site Search**  [45%, 88%, sw]
    8. **Preset Styles**  [51%, 88%, sw]
    9. **RocketLauncher**  [59%, 88%, sw]
    10. **FP MainBottom**  [70%, 11%, se]
    11. **Demo Info**  [82%, 11%, se]
    12. **Inside Metropolis** [82%, 38%, se]
    13. **Contact Us** [82%, 65%, se]
    14. **Copyright Menu** [92%, 36%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [FP Showcase - RokSprocket Features][module1]
2. [FP Feature - RokSprocket Mosaic][module2]
3. [About Metropolis][module3]
4. [From Blog][module4]
5. [Help & Tips][module5]
6. [Our Users][module6]
7. [Site Search][module7]
8. [Preset Styles][module8]
9. [RocketLauncher][module9]
10. [FP MainBottom][module10]
11. [Demo Info][module11]
12. [Inside Metropolis][module12]
13. [Contact Us][module13]
14. [Copyright Menu][module14]

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Metropolis:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](https://rockettheme.com/joomla/extensions/rokutilities)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Metropolis RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Metropolis demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Metropolis template.

Template Settings
-----
The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Metropolis - Home** as it would be used only for the front page of your site.

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

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to `-nov12-home`.

You can also set the Dropdown Menu Offset in order to center the sub-menu as seen in our demo. As an example, we will look at the settings for the Features sub-menu within the **Main Menu** found at the top of the **Home** page.

![][offset]

To get to the screen shown above, you will want to navigate to the **Main Menu** settings page by going to **Administrator -> Menus -> Main Menu** and selecting **Features**. From there, you will want to navigate to the **Dropdown Menu Options** and look at the **Drop-Down Offset (px)** setting. In our demo, we went with a setting of 37. You can adjust this setting to match your individual needs. Keep in mind this offset will only be set for the Features sub-menu and will not impact any other part of the parent menu.

>> The Features sub-menu is an example found in the Metropolis RocketLauncher, your site's contents may vary. The process remains the same, throughout.

[gantry]: http://gantry.org/downloads
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[Metropolis]: assets/metropolis.jpeg
[Metropolis2]: assets/metropolis2.jpeg
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
[mainmenu]: assets/menu_1.jpg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[article]: assets/article.jpg
[offset]: assets/offset.jpg