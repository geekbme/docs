---
title: Myriad: Recreating the Demo - FP SlideShow
description: Your Guide to Recreating Elements of the Myriad Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

FP RokSprocket Features - FP SlideShow
-----

![][demo]

The **RokSprocket Features** module used near the top of the front page is a great way to feature some of your site's more notable articles or areas of interest.

>> NOTE: If you are using the the RocketLauncher, there are some special instructions concerning the handling of the preset images for this module. If you notice your images aren't changing as expected, or if you would like more information on how this was set up, you can find it [here](demo.md#roksprocket-and-rocketlauncher-settings).

We utilized the **Simple** Content Provider, allowing us to create custom content independent of full articles. The **Title**, **Description**, and **Image** fields in each article have been altered. A few examples of these article changes can be found below, excluding the **Image** fields which will likely not work on your local copy as the links will be different.

>> NOTE: The arrow at the bottom of the module, (rt-bottom-arrow) is not functional unless the **System Messages** option is turned **On**. You can find this option by navigating to **Admin > Extend or Extensions > Template Manager > Myriad > Features**.

### Details

![][demo2]

|      Option      |    Setting     |
| :--------------- | :------------- |
| Title            | `FP SlideShow` |
| Show Title       | Hide           |
| Access           | Public         |
| Position         | slideshow      |
| Status           | Published      |
| Content Provider | Simple         |
| Type             | Features       |

### Filtered Article List

#### Article 1

**Title**

~~~ .html
<span class="wow fadeInDown">Focus!</span>
~~~

**Description**

~~~ .html
<span class="wow fadeInUp" data-wow-delay="0.5s">Photo Centric Theme</span>
~~~

#### Article 2

**Title**

~~~
Power!
~~~

**Description**

~~~ .html
Core Gantry Framework
~~~

#### Article 3

**Title**

~~~ .html
Bounce!
~~~

**Description**

~~~ .html
Animated Content Effects
~~~

### Layout Options

![][demo3]

| Option                | Setting               |  
| :-------------------- | :-------------------- |  
| Display Limit         | ∞                     |  
| Theme                 | Full Slideshow        |  
| Article Titles        | Show                  |  
| Article Text          | Show                  |  
| Preview Length        | ∞                     |  
| Strip HTML Tags       | No                    |  
| Arrow Navigation      | Show                  |  
| Pagination            | Hide                  |  
| Animation             | Crossfade             |  
| Autoplay              | Disable               |  
| Autoplay Delay        | 5                     |  
| Image Resize          | Disable               |  
| Default Title         | Default Article Title |  
| Default Article Text  | Default Article Text  |  
| Default Article Image | Default Article Image |  
| Default Link          | Default Article Link  |  

>> The **Full Slideshow** theme is unique to Myriad and was created to give the RokSprocket mode a certain set of attributes that enables it to look the way it does in this template. You can find more information about overriding themes [here](../../extensions/roksprocket/layout_modes.md#custom-layout-theme-overrides).

### Advanced

![][demo4]

|        Option       |             Setting             |
| :------------------ | :------------------------------ |
| Module Class Suffix | `fp-slideshow fp-preset-images` |

>> NOTE: If you are using the RocketLauncher package, and are not wanting to display more than one preset to display your website with Myriad, please remove the 'fp-preset-images' variation in the RokSprocket - Module Suffix field so you can simply use RokSprocket's Image field to display your image.

[demo]: assets/demo_1.jpeg
[demo2]: assets/demo_1a.jpeg
[demo3]: assets/demo_1b.jpeg
[demo4]: assets/demo_1c.jpeg
