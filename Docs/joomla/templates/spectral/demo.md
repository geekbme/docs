---
title: Spectral: Recreating the Demo
description: Your Guide to Recreating Elements of the Spectral Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/spectral:Spectral

---

Introduction
-----

![][spectral2]

Recreating features of the demo site used to show off some of the more interesting aspects of Spectral can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Spectral Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----


Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][spectral]

:   1. **FP RokSprocket Showcase**  [9%, 12%, se]
    2. **FP RokSprocket - Headlines**  [24%, 12%, se]
    3. **RokAjaxSearch**  [24%, 87%, sw]
    4. **Popular Features by RokSprocket**  [28%, 12%, se]
    5. **About Spectral**  [28%, 87%, sw]
    6. **FP RokSprocket - Strips**  [47%, 12%, se]
    7. **Gantry Extras**  [66%, 87%, sw]
    8. **FP Footer Demo Info**  [81%, 12%, se]
    9. **FP Footer Contact Info** [81%, 80%, sw]
    10. **FP Footer Menu** [88%, 15%, se]

We have detailed how to recreate the individual modules and features pictured above in the links below.

1. [FP RokSprocket Showcase][module1]
2. [FP RokSprocket - Headlines][module2]
3. [RokAjaxSearch][module3]
4. [Popular Features by RokSprocket][module4]
5. [About Spectral][module5]
6. [FP RokSprocket - Strips][module6]
7. [Gantry Extras][module7]
8. [FP Footer Demo Info][module8]
9. [FP Footer Contact Info][module9]
10. [FP Footer Menu][module10]

![][comingsoon]

Spectral also features a **Coming Soon** page that counts down to the launch of your site as you are building it. We have [outlined a method][soon] you can use to quickly edit this page for use on your site.

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Spectral:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](https://rockettheme.com/joomla/extensions/rokutilities)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Spectral RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Spectral demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Spectral template.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Spectral - Home** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. Under the **Main Menu** list, you will want to select **Home** in the Menu Assignments tab.

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You can find these settings by navigating to **Admin > Menus > Main Menu > Home**. Once there, you will want to select the **Page Display** tab.

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to `-nov13-home`.

[gantry]: http://gantry.org/downloads
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[spectral]: assets/spectral.jpeg
[spectral2]: assets/spectral2.jpeg
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
[comingsoon]: assets/comingsoon.jpg
[soon]: comingsoon.md
[mainmenu]: assets/menu_1.jpeg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[scroll]: assets/demo_2.jpeg