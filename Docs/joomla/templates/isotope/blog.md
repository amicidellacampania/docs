---
title: Isotope: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Isotope Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/isotope:Isotope

---

# Introduction

The **Blog** example page demonstrates how you can create a beautiful page with the Isotope template. Here is some information to help you replicate this page as it appears in the demo.

# Modules and Particles

Below is a brief rundown of the modules and particles used to make up the demo page.

![](assets/page_blog.jpeg)

:   1. **Header - Custom HTML (Module)** [3%, 45%, se]
    2. **Mainbar - Page Content** [8%, 5%, se]
    3. **Aside - RokAjaxSearch (Module)** [8%, 75%, se]
    4. **Aside - Custom HTML (Module)** [10%, 75%, se]
    5. **Aside - Login (Module)** [18%, 75%, se]
    6. **Aside - Who's Online (Module)** [25%, 75%, se]
    7. **Bottom - Custom HTML (Module)** [84%, 35%, se]

1. [Header](#header-section)
2. [Mainbar](#mainbar-section)
3. [Aside](#aside-section)
4. [Bottom](#bottom-section)

# Header Section

![](assets/page_blog_1.jpeg)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting         |
|:-----------|:----------------|
| Title      | `Blog - Header` |
| Show Title | Hide            |
| Position   | `header-a`      |
| Status     | Published       |

### Particle Settings

| Option                              | Setting                                |
|:------------------------------------|:---------------------------------------|
| CSS Classes                         | `center`, `g-layercontent`, `noborder` |
| Title                               | Blank                                  |
| Intro                               | Blank                                  |
| Grid Column                         | 1 Column                               |
| Info Lists Item 1 Name              | `Our Blog`                             |
| Info Lists Item 1 Image             | Blank                                  |
| Info Lists Item 1 Image Location    | Left                                   |
| Info Lists Item 1 Text Style        | Header                                 |
| Info Lists Item 1 Image Style       | Compact                                |
| Info Lists Item 1 Description       | `Read the Latest News`                 |
| Info Lists Item 1 Tag               | Blank                                  |
| Info Lists Item 1 Sub Tag           | Blank                                  |
| Info Lists Item 1 Label             | Blank                                  |
| Info Lists Item 1 Link              | Blank                                  |
| Info Lists Item 1 Icon              | Blank                                  |
| Info Lists Item 1 Read More Classes | Blank                                  |

# Mainbar Section

![](assets/page_blog_2.jpeg)

The **Mainbar** section includes several articles assigned to the **Joomla Blog** category, displayed through the **Page Content** particle. Here are the settings found in the **Dramatically visualize customer directed convergence without revolutionary ROI** article.

| Option   | Setting                                                                          |
|:---------|:---------------------------------------------------------------------------------|
| Title    | `Dramatically visualize customer directed convergence without revolutionary ROI` |
| Alias    | `dramatically-visualize-customer-directed-convergence-without-revolutionary-roi` |
| Status   | Published                                                                        |
| Featured | No                                                                               |
| Category | `Joomla Blog`                                                                    |

**Content Body**

~~~ .html
<p><img src="images/rocketlauncher/pages/blog/img-01.jpg" alt="Sample Blog"></p>
<p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI. Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>
<a class="button" href="#">Read More</a>
~~~

# Aside Section

![](assets/page_blog_3.jpeg)

:   1. **RokAjaxSearch (Module)** [7%, 15%, se]
    2. **Custom HTML (Module)** [20%, 15%, se]
    3. **Login (Module)** [50%, 15%, se]
    4. **Who's Online (Module)** [80%, 15%, se]

This area of the page consists of the **Aside** section, which sits to the right of the **Mainbar** section in the **Layout Manager**.

Here is a breakdown of the modules used in the `aside` module position assigned to the **Aside** section in the **Layout Manager** for the **Blog** sample page:

* RokAjaxSearch (Module)
* Custom HTML (Module)
* Login (Module)
* Who's Online (Module)

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

## RokAjaxSearch (Module)

The Site Search area of the front page is a **mod_rokajaxsearch** module that allows visitors to search your site using the powerful RokAjaxSearch tool.

### Details

| Option     | Setting           |
|:-----------|:------------------|
| Title      | `Search Our Site` |
| Show Title | Show              |
| Position   | aside             |
| Status     | Published         |
| Access     | Public            |

### Module

| Option                            | Setting                                                  |
|:----------------------------------|:---------------------------------------------------------|
| Search Page URL                   | `index.php?option=com_search&view=search&tmpl=component` |
| Advanced Search Page URL          | `index.php?option=com_search&view=search`                |
| Include RokAjaxSearch default CSS | No                                                       |
| Theme Style                       | Light                                                    |
| Searchphrase                      | Any words                                                |
| Ordering                          | Newest First                                             |
| Limit                             | 10                                                       |
| Results Per Page                  | 3                                                        |
| Google Web Search                 | No                                                       |
| Google Blog Search                | No                                                       |
| Google Images Search              | No                                                       |
| Google Videos Search              | No                                                       |
| Show Pagination                   | Yes                                                      |
| Google SafeSearch                 | Moderate                                                 |
| Image Size to Search              | Medium                                                   |
| Show Estimated                    | Yes                                                      |
| Hide div id(s)                    | Blank                                                    |
| Link to All Results               | Yes                                                      |
| Show Description                  | Yes                                                      |
| Include (Category/Section)        | Yes                                                      |
| Show Read More Link               | Yes                                                      |

### Advanced

| Option              | Setting |
|:--------------------|:--------|
| Module Class Suffix | Blank   |

## Custom HTML (Module)

### Details

| Field      | Setting                                 |
|:-----------|:----------------------------------------|
| Title      | `Sophisticated - Responsive - Powerful` |
| Show Title | Hide                                    |
| Position   | `extension-a`                           |
| Status     | Published                               |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<div class="g-grid">
  <div class="g-block box-grey size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="fa fa-dashboard fa-fw fa-2x"></span> Sophisticated</h2>
      <p>Dynamically procrastinate B2C users after installed base benefits.</p>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="fa fa-arrows-alt fa-fw fa-2x"></span> Responsive</h2>
      <p>Dynamically procrastinate B2C users after installed base benefits.</p>
    </div>
  </div>
  <div class="g-block box-grey size-33-3">
    <div class="g-content ">
      <h2 class="g-title"><span class="fa fa-sliders fa-fw fa-2x"></span> Powerful</h2>
      <p>Dynamically procrastinate B2C users after installed base benefits.</p>
    </div>
  </div>
</div>
~~~

### Basic

| Option                    | Setting |
|:--------------------------|:--------|
| Prepare Content           | No      |
| Select a Background Image | Blank   |

### Advanced

| Option              | Setting |
|:--------------------|:--------|
| Module Class Suffix | Blank   |

## Login (Module)

### Details

| Field      | Setting   |
|:-----------|:----------|
| Title      | `Login`   |
| Show Title | Show      |
| Position   | `aside`   |
| Status     | Published |

### Options

| Field                   | Setting |
|:------------------------|:--------|
| Pre-text                | Blank   |
| Post-text               | Blank   |
| Login Redirection Page  | Default |
| Logout Redirection Page | Default |
| Show Greeting           | Yes     |
| Show Name/Username      | Name    |
| Encrypt Login Form      | No      |
| Display Labels          | Icons   |

### Advanced

| Field               | Setting |
|:--------------------|:--------|
| Module Class Suffix | `box3`  |

## Who's Online (Module)

### Details

| Field      | Setting        |
|:-----------|:---------------|
| Title      | `Who's Online` |
| Show Title | Show           |
| Position   | `aside`        |
| Status     | Published      |

### Options

| Field   | Setting             |
|:--------|:--------------------|
| Display | # of Guests / Users |


### Advanced

| Field               | Setting |
|:--------------------|:--------|
| Module Class Suffix | Blank   |

## Bottom Section

![](assets/page_blog_4.jpeg)

This area of the page is an **Info List** particle. You will find the settings used in our demo below.

### Info List Particle

#### Gantry 5 Particle Module Details

| Field      | Setting                   |
|:-----------|:--------------------------|
| Title      | `Blog - Share Some Ideas` |
| Show Title | Hide                      |
| Position   | `bottom-a`                |
| Status     | Published                 |

#### Particle Settings

| Option                              | Setting                                                       |
|:------------------------------------|:--------------------------------------------------------------|
| CSS Classes                         | `center`, `g-layercontent`, `noborder`                        |
| Title                               | Blank                                                         |
| Intro                               | Blank                                                         |
| Grid Column                         | 1 Column                                                      |
| Info Lists Item 1 Name              | `Share Some Ideas`                                            |
| Info Lists Item 1 Image             | Blank                                                         |
| Info Lists Item 1 Image Location    | Left                                                          |
| Info Lists Item 1 Text Style        | Header                                                        |
| Info Lists Item 1 Image Style       | Compact                                                       |
| Info Lists Item 1 Description       | `Do You Have a Tip or an Idea for a Story? Tell Us About It.` |
| Info Lists Item 1 Tag               | Blank                                                         |
| Info Lists Item 1 Sub Tag           | Blank                                                         |
| Info Lists Item 1 Label             | `Submit Article`                                              |
| Info Lists Item 1 Link              | `http://www.rockettheme.com/joomla/templates/isotope`          |
| Info Lists Item 1 Icon              | Blank                                                         |
| Info Lists Item 1 Read More Classes | Blank                                                         |
