---
title: Plethora: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Plethora Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/plethora:Plethora

---

Introduction
-----

The **Blog** example page demonstrates how you can create a beautiful page with the Plethora template. Here is some information to help you replicate this page as it appears in the demo.

Menu Item Options
-----

![][blogpage2]

The **Blog** page is a **Category Blog** menu item type. To recreate the layout the way it appears in our demo, enter `blog` in the **Alias** field in the menu item settings. This alias is tied to a class in the demo.less file.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Administrator > Template Manager > Template > Advanced**.

Mainbody
-----

![][blogpage9]

The page's content body is set to display articles in the **Sample Blog** category. The first article is the **Powered by Gantry Framework** article. You will find the content used in the article below.

~~~ .html
<p><span class="rt-image"><img src="images/rocketlauncher/pages/blog/img-01.jpg" alt="image" /></span></p>
<p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>
<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>
~~~

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![][blogpage]

:   1. **Custom HTML - Blog** [9%, 45%, se]
    2. **RokAjaxSearch - Search the Blog** [14%, 85%, sw]
    3. **Menu Module - Site Menu** [18%, 85%, sw]
    4. **Custom HTML - Template Tutorials** [45%, 85%, sw]
    5. **Login Form - Login Form** [55%, 85%, sw]
    6. **Who's Online - Who's Online** [65%, 85%, sw]
    7. **Custom HTML - Join Our Newsletter** [81%, 44%, se]
    8. **Custom HTML - Plethora Demo** [87%, 15%, se]
    9. **Custom HTML - Sample Contact Info** [87%, 50%, se]
    10. **Category Blog** [15%, 55%, sw]

1. [Custom HTML - Blog](blog.md#custom-html---blog)
2. [RokAjaxSearch - Search the Blog](blog.md#rokajaxsearch---search-the-blog)
3. [Menu Module - Site Menu](blog.md#menu-module---site-menu)
4. [Custom HTML - Template Tutorials](blog.md#custom-html---template-tutorials)
5. [Login Form - Login Form](blog.md#login---login-form)
6. [Who's Online - Who's Online](blog.md#who's-online---who's-online)
7. [Custom HTML - Join Our Newsletter](blog.md#custom-html---join-our-newsletter)
8. [Custom HTML - Plethora Demo](blog.md#custom-html---plethora-demo)
9. [Custom HTML - Sample Contact Info](blog.md#custom-html---sample-contact-info)
10. [Category Blog](blog.md#mainbody)

### Custom HTML - Blog

![][blogpage3]

#### Module

| Option      | Setting                                                      |
| :---------- | :-----------                                                 |
| Title       | `Blog[span class="rt-title-tag"]Read the Latest News[/span]` |
| Show Title  | Show                                                         |
| Position    | top-a                                                        |
| Status      | Published                                                    |
| Access      | Public                                                       |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

#### Content

~~~ .html
&nbsp;
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option                    | Setting                                       |
| :----------               | :----------                                   |
| Module Class Suffix       | `rt-center rt-title-large rt-nomodulecontent` |

### RokAjaxSearch - Search the Blog

![][blogpage4]

#### Module

| Option                            | Setting                                                  |
| :----------                       | :-----------                                             |
| Title                             | `Search the Blog`                                        |
| Show Title                        | Show                                                     |
| Position                          | sidebar-a                                                |
| Status                            | Published                                                |
| Access                            | Public                                                   |
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Engine URL        | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Blue                                                     |
| Searchphrase                      | Any Words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results per page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Google Ajax Search API Key        |                                                          |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimates                    | Yes                                                      |
| Hide div id(s)                    |                                                          |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include Category/Section          | Yes                                                      |
| Show Read More Link               | Yes                                                      |

#### Advanced

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `box2 title2` |

### Menu Module - Site Menu

![][blogpage5]

#### Module

| Option              | Setting      |
| :----------         | :----------- |
| Title               | `Site Menu`  |
| Show Title          | Show         |
| Position            | sidebar-a    |
| Status              | Published    |
| Access              | Public       |
| Select Menu         | Main Menu    |
| Base Item           | Current      |
| Start Level         | 1            |
| End Level           | All          |
| Show Sub-Menu Items | Yes          |

#### Advanced

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `box3 title3` |

### Custom HTML - Template Tutorials

![][blogpage6]

#### Module

| Option      | Setting              |
| :---------- | :-----------         |
| Title       | `Template Tutorials` |
| Show Title  | Show                 |
| Position    | sidebar-a            |
| Status      | Published            |
| Access      | Public               |

#### Content

~~~ .html
<ul>
    <li><a href="http://www.rockettheme.com/docs/joomla/platform/templates.md#how-to-install">How to Install</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_edit_the_logo.md">Change the Default Logo</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_edit_template_text.md">Editing Template Text</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_set_up_a_rokbox_member_login.md"><span class="hidden-tablet">Set Up a </span>RokBox Member Login</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_use_popup_module.md"><span class="hidden-tablet">How to Use the </span>Popup Module</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/responsive_support_classes.md">Responsive Support Classes</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/creating_responsive_content.md"><span class="hidden-tablet">Creating </span>Responsive Content</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/k2_styling_guide.md">K2 Styling Guide</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/basic/how_to_create_a_template_override.md"><span class="hidden-tablet">How to Create a </span>Template Override</a></li>
    <li><a href="http://www.rockettheme.com/docs/joomla/templates/plethora/demo.md">Recreating the Demo</a></li>
</ul>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting       |
| :----------         | :----------   |
| Module Class Suffix | `box1 title1` |

### Login - Login Form

![][blogpage7]

#### Module

| Option                  | Setting      |
| :----------             | :----------- |
| Title                   | `Login Form` |
| Show Title              | Show         |
| Position                | sidebar-a    |
| Status                  | Published    |
| Access                  | Public       |
| Pre-text                |              |
| Post-test               |              |
| Login Redirection Page  | Default      |
| Logout Redirection Page | Default      |
| Show Greeting           | Yes          |
| Show Name/Username      | Name         |
| Encrypt Login Form      | No           |
| Display Labels          | Icons        |

#### Advanced

| Option              | Setting       |
| :----------         | :-----------  |
| Module Class Suffix | `box4 title4` |

### Who's Online - Who's Online

![][blogpage8]

#### Module

| Option      | Setting             |
| :---------- | :-----------        |
| Title       | `Who's Online`      |
| Show Title  | Show                |
| Position    | sidebar-a           |
| Status      | Published           |
| Access      | Public              |
| Display     | # of Guests / Users |

#### Advanced

| Option              | Setting      |
| :-----------        | :----------- |
| Module Class Suffix | `title1`     |

### Custom HTML - Join Our Newsletter

![][blogpage10]

#### Module

| Option      | Setting               |
| :---------- | :-----------          |
| Title       | `Join Our Newsletter` |
| Show Title  | Yes                   |
| Position    | extension-a           |
| Status      | Published             |
| Access      | Public                |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-60 gantry-block-center">
        <div class="gantry-width-spacer">
            <p><span>Get Updates, Upcoming Themes Info, and Our Great Deals!</span></p>
            <form class="rt-blog-form largemargintop largepaddingtop" action="http://feedburner.google.com/fb/a/mailverify" method="post" target="popupwindow" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true">
                <input type="text" placeholder="Your Email" alt="Your Email" class="inputbox" name="email">
                <input type="hidden" value="rocketthemeblog" name="uri" />
                <input type="hidden" name="loc" value="en_US" />
                <input type="submit" name="Submit" class="readon" value="Join" />
            </form>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting     |
| :----------         | :---------- |
| Module Class Suffix | `rt-center` |

### Custom HTML - Plethora Demo

![][blogpage11]

#### Module

| Option      | Setting          |
| :---------- | :-----------     |
| Title       | `Plethora Demo` |
| Show Title  | Yes              |
| Position    | footer-a         |
| Status      | Published        |
| Access      | Public           |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Plethora can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>
<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/plethora">Plethora RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

### Custom HTML - Sample Contact Info

![][blogpage12]

#### Module

| Option      | Setting               |
| :---------- | :-----------          |
| Title       | `Sample Contact Info` |
| Show Title  | Yes                   |
| Position    | footer-b              |
| Status      | Published             |
| Access      | Public                |

#### Content

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>
<div class="gantry-width-40">
	<div class="gantry-width-spacer">
		<img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" />
	</div>
</div>
<div class="gantry-width-60">
	<div class="gantry-width-spacer">
		<span class="rt-intro-text">+1(123)456-5555-555</span><br />
		<span>Plethora Theme, LLC</span><br />
		<span>123 Joomla! Boulevard</span><br />
		<span>Seattle, WA 00000, USA</span><br />
		<span><a href="#">noreply@domain.com</a></span>
	</div>
</div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

[blogpage]: assets/page_blog.jpeg
[blogpage2]: assets/page_blog_2.jpeg
[blogpage3]: assets/page_blog_3.jpeg
[blogpage4]: assets/page_blog_4.jpeg
[blogpage5]: assets/page_blog_5.jpeg
[blogpage6]: assets/page_blog_6.jpeg
[blogpage7]: assets/page_blog_7.jpeg
[blogpage8]: assets/page_blog_8.jpeg
[blogpage9]: assets/page_blog_9.jpeg
[blogpage10]: assets/page_blog_10.jpeg
[blogpage11]: assets/page_blog_11.jpeg
[blogpage12]: assets/page_blog_12.jpeg
[blogpage13]: assets/page_blog_13.jpeg
