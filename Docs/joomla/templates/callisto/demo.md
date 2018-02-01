---
title: Callisto: Recreating the Demo
description: Your Guide to Recreating Elements of the Callisto Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/callisto:Callisto

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Callisto can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Callisto Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module and Particle Settings
-----

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/callisto2.jpeg)

:   1. **Header - Logo** [5%, 12%, se]
    2. **Header - Icon Menu** [5%, 55%, se]
    3. **Navigation - Menu** [8%, 12%, se]
    4. **Navigation - Social** [9%, 80%, se]
    5. **Showcase - Module Position (showcase)** [12%, 13%, se]
    6. **Mainfeature - Content List** [25%, 12%, se]
    7. **Sidefeature - Module Position (sidefeature-a)** [25%, 65%, se]
    8. **Sidefeature - Module Position (sidefeature-b)** [30%, 65%, se]
    9. **Main - Content List** [42%, 12%, se]
    10. **Main - Custom HTML** [42%, 63%, se]
    11. **Extension - Module Position (extension-a)** [51%, 12%, se]
    12. **Extension - Module Position (extension-b)** [55%, 12%, se]
    13. **Extension - Promo Image** [70%, 12%, se]
    14. **Extension - Module Position (extension-c)** [70%, 38%, se]
    15. **Extension - Image Grid** [70%, 65%, se]
    16. **Footer - Info List** [80%, 12%, se]
    17. **Footer - Custom HTML** [80%, 38%, se]
    18. **Footer - Contact** [80%, 63%, se]
    19. **Copyright - Copyright** [91%, 38%, se]

We have detailed how to recreate the individual modules and particles pictured above in the links below, separated by sections found in the **Layout Manager**.

1. [Header](demo_header.md)
2. [Navigation](demo_navigation.md)
3. [Showcase](demo_showcase.md)
4. [Mainfeature](demo_mainfeature.md)
5. [Sidefeature](demo_sidefeature.md)
6. [Main](demo_main.md)
7. [Extension](demo_extension.md)
8. [Footer](demo_footer.md)
9. [Copyright](demo_copyright.md)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

### Theme Particles

- [Contact](particle_contact.md)
- [Content List](particle_contentlist.md)
- [Content Tabs](particle_contenttabs.md)
- [Features Slider](particle_featuresslider.md)
- [Joomla Content](particle_joomla.md)
- [Headlines](particle_headlines.md)
- [Icon Menu](particle_iconmenu.md)
- [Image Grid](particle_image.md)
- [Info List](particle_info.md)
- [Lists](particle_lists.md)
- [Newsletter](particle_newsletter.md)
- [Promo Image](particle_promoimage.md)

### Core Particles 

- [Logo](http://docs.gantry.org/gantry5/particles/logo)
- [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
- [To Top](http://docs.gantry.org/gantry5/particles/to-top)
- [Social](http://docs.gantry.org/gantry5/particles/social)
- [Positions](http://docs.gantry.org/gantry5/particles/position)
- [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
- [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
- [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
- [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
- [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Callisto:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokAjaxSearch](http://www.rockettheme.com/joomla/extensions/rokajaxsearch)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket](http://www.rockettheme.com/joomla/extensions/roksprocket)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Callisto RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Callisto demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Callisto demo.

Menu Editor
-----

![](assets/menu_1.jpeg)

Callisto has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any chances made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Gantry 5 > Callisto > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Gantry 5 > Callisto** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
