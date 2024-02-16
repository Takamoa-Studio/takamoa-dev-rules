# File Naming Convention for WordPress Development

This document outlines the file naming convention adopted by Takamoa for the development of WordPress themes and plugins, ensuring consistency and ease of maintenance across our projects.

## Contents

- [Introduction](#introduction)
- [Naming Convention](#naming-convention)
- [Examples](#examples)
- [Conclusion](#conclusion)

## Introduction

A consistent naming convention is crucial for efficient development and maintenance of WordPress projects. It facilitates codebase navigation and improves readability for all team developers.

## Naming Convention

Files are named based on their type and function in the project. The general format is:

```
[type]-takamoa-[function-name].[js|css]
```

### Types

- **Shortcode (`sc`)**: For customizations specific to shortcodes.
- **Template Part (`tp`)**: For modifications to template parts (header, footer, etc.).
- **Custom Post Type (`cpt`)**: For styles or scripts related to specific custom post types.
- **Widget (`wd`)**: For styles or functionalities of widgets.
- **Plugin (`pl`)**: For customizations of third-party plugins.
- **Admin (`admin`)**: For WordPress admin area customizations.
- **Theme (`th`)**: For theme-specific overrides or enhancements.
- **Utility (`util`)**: For general utility scripts or styles.
- **Experimental (`exp`)**: For testing new features or experimental code.

## Examples

- **Shortcode for a job listing**: `sc-takamoa-job-list.css` for styles specific to the `job-list` shortcode.
- **Header navigation customization**: `tp-takamoa-header-navigation.css` for styling the header navigation.
- **Product custom post type**: `cpt-takamoa-product-launch.js` for JavaScript functionalities specific to the `Product` custom post type.
- **Recent posts widget**: `wd-takamoa-recent-posts.css` for styling the recent posts widget.
- **Customization for Contact Form 7**: `pl-takamoa-contact-form-7.js` for custom JavaScript on the Contact Form 7 plugin.
- **Admin dashboard styles**: `admin-takamoa-dashboard.css` for custom styles within the WordPress admin dashboard.
- **Custom layouts for the theme**: `th-takamoa-custom-layouts.css` for additional custom layouts in your theme.
- **Global utility functions**: `util-takamoa-global-functions.js` for JavaScript functions used site-wide.
- **Prototype for a new feature**: `exp-takamoa-new-feature-prototype.js` for JavaScript related to a new feature in the prototype stage.

## Conclusion

This naming convention is implemented to ensure a clear and maintainable structure for our WordPress projects. It should be followed by all developers contributing to the project. For any exceptions or proposed changes, please consult the development team.
