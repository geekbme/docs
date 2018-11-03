---
title: Stratos: Recreating the Demo
description: Your Guide to Recreating Elements of the Stratos Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Stratos:Stratos

---

Introduction
-----

![][stratos]

Recreating features of the demo site used to show off some of the more interesting aspects of Stratos can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Stratos Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----


Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][stratos2]

:   1. **Member Access**  [9%, 81%, sw]
    2. **RokSprocket Strips - Showcase**  [15%, 20%, se]
    3. **Site Search**  [30%, 82%, sw]
    4. **About Stratos**  [35%, 82%, sw]
    5. **RokSprocket Strips - MainBottom**  [49%, 20%, se]
    6. **RokSprocket Tabs**  [63%, 20%, se]
    7. **Gantry Extras**  [63%, 82%, sw]
    8. **Footer A**  [78%, 20%, se]
    9. **Footer B**  [78%, 82%, sw]
    10. **Copyright Menu**  [88%, 65%, sw]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [Member Access][module1]
2. [FP RokSprocket Strips - Showcase][module2]
3. [Site Search][module3]
4. [About Stratos][module4]
5. [FP RokSprocket Strips - MainBottom][module5]
6. [FP RokSprocket Tabs][module6]
7. [Gantry Extras][module7]
8. [FP Footer A][module8]
9. [FP Footer B][module9]
10. [Copyright Menu][module10]

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Stratos:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](https://rockettheme.com/joomla/extensions/rokutilities)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Stratos RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Stratos demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Stratos template.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Stratos - Home** as it would be used only for the front page of your site.

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

You will need to change the **Page Class** setting under the Home menu item to `jul13-home`.

The icons that appear at the top-level menu area are configured under the individual menu item's **Dropdown Menu Options**, and are set in the **Menu Icon** option.

For example, the **Home** menu icon is set to `icon-home`. For a full list of icons you can choose from, check out [this list by Font Awesome][icons].

Article Settings
-----

![][article]

The two articles that appear on the front page of the Stratos demo utilize a preset **Intro Image** under the **Images and Links** menu within the article's individual **Article Manager** page.

For example, the **RokSprocket Styling** article preview as it appears in the **MainBody** section of the front page has an **Intro Image** set.

To replicate this specific layout, the publishing date needs to be used.

[gantry]: http://gantry.org/downloads
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[stratos2]: assets/stratos2.jpg
[stratos]: assets/stratos.jpg
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
[mainmenu]: assets/menu_1.jpeg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[article]: assets/article.jpg