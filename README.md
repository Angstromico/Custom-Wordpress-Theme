# ManuelTheme - Custom WordPress Theme

A custom WordPress theme built following the FreeCodeCamp "How to Create a Custom WordPress Theme - Full Course" tutorial.

## About

ManuelTheme is a custom WordPress theme developed as a learning project based on the comprehensive FreeCodeCamp course. This theme demonstrates the fundamental structure and functionality of a WordPress theme, implementing best practices and modern WordPress development standards.

## Features

- **Responsive Design**: Mobile-first approach with responsive layouts
- **WordPress Standards**: Follows WordPress coding standards and best practices
- **Template Hierarchy**: Complete WordPress template hierarchy implementation
- **Custom Functions**: Theme-specific functionality through `functions.php`
- **Asset Management**: Organized CSS and JavaScript assets
- **SEO Friendly**: Semantic HTML5 structure with proper meta tags
- **Accessibility**: WCAG compliant markup and ARIA attributes

## Theme Structure

```
manueltheme/
├── 404.php           # 404 error page template
├── archive.php       # Archive page template
├── assets/           # CSS, JavaScript, and image assets
├── classes/          # PHP classes for theme functionality
├── comments.php      # Comments template
├── footer.php        # Footer template
├── functions.php     # Theme functions and setup
├── header.php        # Header template
├── inc/              # Include files and theme modules
├── index.php         # Main index template
├── page.php          # Single page template
├── readme.txt        # WordPress theme readme
├── README.md         # This file
├── screenshot.png    # Theme screenshot for WordPress admin
├── search.php        # Search results template
├── single.php        # Single post template
├── style.css         # Main stylesheet with theme header
├── template-parts/   # Reusable template parts
└── templates/        # Custom page templates
```

## Installation

1. **Download the Theme**: Clone or download this repository to your local machine
2. **Upload to WordPress**: 
   - Navigate to `wp-content/themes/` in your WordPress installation
   - Create a new folder named `manueltheme`
   - Copy all theme files into this folder
3. **Activate the Theme**:
   - Log in to your WordPress admin dashboard
   - Go to **Appearance → Themes**
   - Find "ManuelTheme" and click **Activate**

## Requirements

- WordPress 5.0 or higher
- PHP 7.4 or higher
- Modern web browser

## Development

### Based On

This theme was created following the FreeCodeCamp tutorial:
**"How to Create a Custom WordPress Theme - Full Course"**
- **YouTube**: https://www.youtube.com/watch?v=-h7gOJbIpmo
- **Instructor**: FreeCodeCamp.org

### Key Concepts Covered

- WordPress template hierarchy
- Theme functions and hooks
- Enqueuing styles and scripts
- Custom post types and taxonomies
- WordPress customizer integration
- Widget areas and menus
- Security best practices
- Performance optimization

### Customization

To customize this theme:

1. **Colors and Typography**: Edit `style.css` or use the WordPress Customizer
2. **Layout**: Modify template files in the root directory or `template-parts/`
3. **Functionality**: Add custom functions to `functions.php` or create new files in `inc/`
4. **Assets**: Add CSS, JavaScript, and images to the `assets/` directory

## Theme Support

This theme supports the following WordPress features:

- Post thumbnails
- Custom logo
- Custom background
- Custom header
- Navigation menus
- Widget areas
- HTML5 markup
- Title tag
- Automatic feed links

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

This is a learning project. Feel free to:
- Fork the repository
- Create feature branches
- Submit pull requests
- Report issues

## License

This theme is open source and available under the [GNU General Public License v2 or later](https://www.gnu.org/licenses/gpl-2.0.html).

## Author

Developed as a learning project following FreeCodeCamp's WordPress theme development course.

## Changelog

### Version 1.0.0
- Initial theme setup
- Basic WordPress template structure
- Theme activation and functionality
- Responsive layout implementation

---

**Note**: This theme was created for educational purposes following the FreeCodeCamp WordPress theme development tutorial. It serves as a foundation for understanding WordPress theme development principles.
