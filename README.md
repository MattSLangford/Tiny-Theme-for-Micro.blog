# Tiny-Theme-for-Micro.blog
A custom theme for Micro.blog. It includes micro.blog specific features and an automatic dark mode (loosely based on Dracula). It has no additional scripts, no custom fonts, and only 1 media query (for dark mode). It has full support for default comments, the reply by email plugin, and the conversation on Micro.Blog plugin.

### Screenshots
![Tiny Theme Light](https://github.com/MattSLangford/Tiny-Theme-for-Micro.blog/blob/main/screenshot.png?raw=true)
![Tiny Theme Dark](https://github.com/MattSLangford/Tiny-Theme-for-Micro.blog/blob/main/screenshot2.png?raw=true)

### Demo
You can demo the current version of this theme by visiting [mattlangford.com](https://mattlangford.com).

### Installation
This theme is now listed in the plugins directory of Micro.blog. You can install with one click there.

### Required Settings
Once the theme is installed and active on your site, navigate to the theme settings and add your short bio.

### Support
If you're having any trouble, feel free to [contact me](https://mattlangford.com/contact/).

### Modifications

#### Adding/Editing the Footer
The Tiny Theme uses Micro.blog's default Custom Footer options. In the Micro.blog "Design" section of your dashboard, click "Edit Footer". Any content added here will show in the footer of your site.

#### Design Changes
To tweak the design, use the "Edit CSS" option in the "Design" section of your Micro.blog dashboard. If you're familiar with CSS, you can dive right in. If not, here are a few example snippets to get you started.

##### Overall Site Size
While you can dig way into the CSS and individually manipulate each individual element on its own, I've created this theme to dynamically alter the entire design based on the font-size. By default, the theme uses a font-size of 18px. While you can change that to any value, I suggested keeping it between 14-22px. Copy the following code and choose your size.

```
body {font-size: 18px;}
```

##### Remove Categories from Single Posts
```
ul.post-tags {display: none;}
```

##### Modifying the Colors
All colors for the site are created using CSS custom properties (or variables). This may sound complicated, but it greatly simplifies making wholesale changes to the color scheme. The following snippet includes every default color for both light and dark modes.

```
/*Light mode*/
:root {
	--text: #000000;
	--link: #0000EE;
	--link_visited: #551A8B;
	--accent1: #333333;
	--accent2: #666666;
	--background: #ffffff;
	--code: #e3e3e3;
	--button-text: #ffffff;
	--blockquote: #fffee0;
}

/* Dark mode */
@media (prefers-color-scheme: dark) {
	:root {
		--text: #f8f8f2;
		--link: #8be9fd;
		--link_visited: #ff79c6;
		--accent1: #f8f8f2;
		--accent2: #f8f8f2;
		--background: #282a36;
		--code: #44475a;
		--button-text: #282a36;
		--blockquote: #44475a;
	}
}
```

If you'd like to change a certain color, you only need to include that particular color in your custom CSS. For example, let's change the link value to a red color on both light and dark modes.

```
:root {
	--link: #8B0000;
}

@media (prefers-color-scheme: dark) {
	:root {
		--link: #8B0000;
	}
}
```

If you'd like to change further colors, just update the above snippet to include those as well.
