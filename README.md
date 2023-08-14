# WordPress Plugin

This WordPress plugin allows you to easily create and manage a slideshow of images using shortcodes. You can upload, remove, and reorder images from the admin settings page and display the slideshow on any page or post using shortcode.

## Table of Contents

- [Installation](#installation)
- [Admin-Side Settings](#admin-side-settings)
- [Front-End Usage](#front-end-usage)
- [Supported jQuery Libraries](#supported-jquery-libraries)
- [Customization](#customization)
- [Contributions](#contributions)

## Installation

1. Upload the `WordPress-Plugin` folder to the `wp-content/plugins/` directory of your WordPress installation.
2. Activate the plugin through the 'Plugins' menu in the WordPress admin panel.

## Admin-Side Settings

1. After activation, navigate to the 'Upload Photos Setting' section in the sidebar of the WordPress Dashboard.
2. To add or edit a gallery, click on the 'Upload Image' button within the 'Add New/Edit Gallery' page.
3. Choose the images you'd like to include in the gallery and save them.
4. Rearrange the order of the images by dragging them around within the gallery.
5. Once you're satisfied, click the 'Publish' button to save your changes.

## Front-End Usage

1. After creating or editing a gallery, a button will appear that shows the shortcode associated with the gallery.
2. The shortcode will look something like this: `[rtc_challenge_a id=""]`.
3. Copy the generated shortcode.
4. Navigate to your desired post or page.
5. In the post editor, paste the shortcode where you want the slideshow to appear.
6. Update or publish your post/page.

Upon rendering, the shortcode will dynamically generate a slideshow containing the images you've uploaded via the admin settings page.

## Supported jQuery Libraries

This plugin provides flexibility in choosing your preferred jQuery slideshow library or plugin. Some popular options include:

- [Slick Slider](https://kenwheeler.github.io/slick/)
- [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/)

Ensure that you enqueue the necessary scripts and styles for your chosen library within your plugin's code.

## Customization

The plugin's appearance and behavior can be customized to align with your site's design and requirements. CSS and JavaScript files for customization are located in the `custom-slideshow` plugin folder.

## Contributions

Contributions are highly appreciated! If you wish to contribute, please submit a pull request with your proposed changes.
