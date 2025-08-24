# Font Awesome Elite

:zap: Font Awesome Elite for [all Font Awesome icons](https://fontawesome.com/icons)!

:unlock: Font Awesome Elite supports all icons from Font Awesome's [Free](https://fontawesome.com/search?ic=free), [Pro](https://fontawesome.com/search?ic=pro-collection), and [Pro+](https://fontawesome.com/search?ic=pro-plus-collection) packages.

***

## :blue_book: Documentation

Font Awesome Elite uses [Font Awesome documentation](https://docs.fontawesome.com).

The development of Font Awesome Elite follows the development of Font Awesome, and the core of Font Awesome Elite has the same structure as the core of Font Awesome. Thus, Font Awesome Elite uses the Font Awesome documentation.

***

## :gear: Usage

To use Font Awesome Elite, use its CDN links or download it locally.

#### :globe_with_meridians: Using CDN :

Font Awesome Elite uses [jsDelivr](https://jsdelivr.com) for CDN.

To use Font Awesome Elite, you can use its CDN links :

```html
<!-- Font Awesome Elite's core CSS file -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/fontawesome.css" integrity="" crossorigin="anonymous">
<!-- Font Awesome Elite's icon families CSS files -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/brands.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/solid.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/light.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/thin.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/duotone.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/duotone-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/duotone-light.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/duotone-thin.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-solid.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-light.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-thin.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-duotone-solid.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-duotone-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-duotone-light.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/sharp-duotone-thin.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/chisel-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/etch-solid.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/jelly-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/jelly-fill-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/jelly-duo-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/notdog-solid.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/notdog-duo-solid.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/slab-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/slab-press-regular.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/thumbprint-light.css" integrity="" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/whiteboard-semibold.css" integrity="" crossorigin="anonymous">
```

Copy the `<link>` element that serves the core CSS file (**fontawesome.css**) of Font Awesome Elite's and the `<link>` element that serves the CSS file (*for example **light.css***) of the icon family you want to use, or the `<link>` elements that serves the CSS files (*for example **thin.css**, **duotone-thin.css**, **notdog-solid.css**, etc.*) of the icon families you want to use, inside the `<head>` element of your project.

If you are going to use all icon families in your project, copy the `<link>` element that serves the **fontawesome-elite.css** file, which contains the CSS files for all icon families, inside the `<head>` element of your project :

```html
<!-- CSS file of all icon families of Font Awesome Elite -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/elmarmehrabov/Font-Awesome-Elite@main/css/fontawesome-elite.css" integrity="" crossorigin="anonymous">
```

This file also contains the core CSS file (**fontawesome.css**) of Font Awesome Elite.

#### :computer: Local use :

To use Font Awesome Elite, you can download it locally. Using Font Awesome Elite locally is similar to using it from a CDN. The difference between using Font Awesome Elite locally and using it from a CDN is simply the paths to the CSS files.

To do this, first download the **font-awesome-elite-x.x.x.zip** file, the latest version of Font Awesome Elite, from the [Releases](https://github.com/elmarmehrabov/Font-Awesome-Elite/releases) page. The **font-awesome-elite-x.x.x.zip** file is the **font-awesome-elite-x.x.x** folder. This folder contains a **css** folder containing the CSS files for all icon families, and a **webfonts** folder containing the font files for all icon families. Extract the downloaded **font-awesome-elite-x.x.x.zip** file to a location of your choice in your project.

So, you can use Font Awesome Elite natively in your project by adapting the references of the following `<link>` elements to your project :

```html
<!-- Font Awesome Elite's core CSS file -->
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/fontawesome.css">
<!-- Font Awesome Elite's icon families CSS files -->
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/brands.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/solid.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/light.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/thin.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/duotone.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/duotone-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/duotone-light.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/duotone-thin.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-solid.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-light.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-thin.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-duotone-solid.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-duotone-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-duotone-light.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/sharp-duotone-thin.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/chisel-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/etch-solid.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/jelly-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/jelly-fill-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/jelly-duo-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/notdog-solid.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/notdog-duo-solid.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/slab-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/slab-press-regular.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/thumbprint-light.css">
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/whiteboard-semibold.css">
```

Copy the `<link>` element of the core CSS file (**fontawesome.css**) of Font Awesome Elite and the `<link>` element of the CSS file (*for example **light.css***) of the icon family you want to use, or the `<link>` elements of the CSS files (*for example **thin.css**, **duotone-thin.css**, **notdog-solid.css**, etc.*) of the icon families you want to use, inside the `<head>` element of your project. Then adapt the references of those `<link>` elements to your project.

If you are going to use all icon families in your project, copy the `<link>` element of the **fontawesome-elite.css** file, which contains the CSS files for all icon families, inside the `<head>` element of your project. Then adapt the reference of that `<link>` element to your project :

```html
<!-- CSS file of all icon families of Font Awesome Elite -->
<link rel="stylesheet" href="your-path/font-awesome-elite-x.x.x/css/fontawesome-elite.css">
```

This file also contains the core CSS file (**fontawesome.css**) of Font Awesome Elite.

#### :large_blue_circle: Using icon :

For example, it is shown below how you can use the file icon in the light style of the duotone icon family in your project :

```html
<i class="fa-duotone fa-light fa-file"></i>
```

You can learn more about how to use icons in your project on the [How To Add Icons](https://docs.fontawesome.com/web/add-icons/how-to) page of the Font Awesome documentation.

***

## :round_pushpin: Versioning

Font Awesome Elite uses the [Semantic Versioning](https://semver.org) (SemVer) standard for versioning.

***

## :page_facing_up: License

[License](https://github.com/elmarmehrabov/Font-Awesome-Elite/blob/main/LICENSE)
