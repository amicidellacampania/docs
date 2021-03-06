---
title: Editor Button

---

Editor Button
-----

RokBox has a built-in editor button that integrates with the Joomla content, and can be used to easily generate RokBox snippets.

![][rokbox2-editor-button]

:   1. **Link Property** **(mandatory)** The link you wish to link to. It can be a YouTube link, a local image, a remote image, etc. [22%, 22%, se]
    2. **DOM Element** Specify a CSS rule that matches the element in the page you want to render in the popup. [28%, 22%, se]
    3. **Album** This field can be any string. It allows a set of RokBox2 links to be grouped so the user can navigate through them. [42%, 22%, se]
    4. **Caption**  [50%, 22%, se]
    4. **Content** This item has an Caption [56%, 22%, se]

The Editor Button popup is meant to be as user-friendly as possible and as can be noticed from the screenshot above, it is very self explanatory.

Link
----

The link is the only **required** field that needs to be filled out. It could be a local image, a YouTube video, a remote URL, or anything that [RokBox 2 supports][key-features].

The link field also provides an image picker. On the right side of the input field you can click the icon to pick an image from the Joomla Media Manager.

>> By default, Joomla Media Manager loads images from `images/`. This can be changed from **Content -> Media Manager -> Options**.


DOM Element
-----------

The **DOM Element** field takes a CSS-Style syntax value that needs to be targeting an **Element** in the page. Whenever you start filling this field, the [Link][link] will get disabled and auto-populated with an hash `#`.
This is because a DOM Element type link is not a true link, and does not point to any actual URL.

More details on how DOM Element works, and how to use it, can be [found here][data-rokbox-element].


Album
-----

The **Album** field can be any string and allows a set of RokBox2 links to be grouped, so the user can navigate through them. Whenever you decide to create an album, you should use the same album name across the links you want to be grouped.

>> NOTE: The album name is just an identifier for RokBox2, and will never be seen by the end-user. For this reason, it is highly suggested to keep the name as simple as possible, to avoid potential misinterpretations by RokBox2.

More details on how Album works, and how to use it, can be [found here][data-rokbox-album].


Caption
-------

This is the **Caption** associated to the link that RokBox2 will show. This field takes simple text, as well as HTML syntax. When inserting the Snippet, any HTML syntax will get automatically converted into HTML entities.

>> NOTE: Extremely long captions might cause undesired results. The main goal of RokBox is to display images and other media formats. Try to keep the caption short and concise.

More details on how Caption works, and how to use it, can be [found here][data-rokbox-caption].


Content
-------

The content is what will be wrapped by the RokBox2 `<a>` link. It could be either text or an image.

If you decide to have text as content, you can either have it being plain text or HTML syntax. Differently from [the caption][caption], the HTML syntax written in the Content will be kept intact.

If you decide to have an image as content, you can either have it [auto-generated][data-rokbox-generate-thumbnail] or like for the [Link field][link], you can use the picker to choose a local image.

[key-features]: INDEX.md#key-features
[link]: #link
[caption]: #caption
[data-rokbox-element]: how_to_use.md#data-rokbox-element
[data-rokbox-album]: how_to_use.md#data-rokbox-album
[data-rokbox-caption]: how_to_use.md#data-rokbox-caption
[data-rokbox-generate-thumbnail]: how_to_use.md#data-rokbox-generate-thumbnail
[rokbox2-editor-button]: assets/rokbox2-editor-button.png
