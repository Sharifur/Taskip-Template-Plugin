# Taskip Templates Library

A WordPress plugin that provides a beautiful and efficient way to showcase and manage business templates, such as agreements, proposals, contracts, SOPs, and scope of work documents.

## Description

Taskip Templates Library is a powerful WordPress plugin designed to help businesses and professionals manage and display their document templates. It provides a searchable, categorized interface for accessing various business documents.

Visit [Taskip Templates Library](https://taskip.net/templates/) to see it in action.

## Features

- **Template Management**: Easily add, edit, and organize business templates
- **Categories & Industries**: Organize templates by type and industry
- **Live Search**: Ajax-powered search functionality with debounce support
- **Responsive Design**: Works seamlessly across all devices
- **Custom Taxonomies**:
  - Template Types (agreements, proposals, contracts, etc.)
  - Industries (tech, healthcare, construction, etc.)
- **Preview Support**: Allow users to preview templates before use
- **Easy Integration**: Works with any WordPress theme

## Installation

1. Download the plugin from [Taskip Templates Library](https://taskip.net/templates/)
2. Upload the `taskip-template` folder to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Go to 'Templates' in your WordPress admin menu to start adding templates

## Usage

### Adding a New Template

1. Go to Templates > Add New
2. Enter the template title
3. Add template description
4. Upload preview image (recommended size: 800x600px)
5. Add template URL
6. Select template type and industry
7. Publish

### Managing Templates

- Navigate to Templates > All Templates to view and manage existing templates
- Use the quick edit and bulk actions for efficient management
- Filter templates by type or industry

### Shortcodes

The plugin provides three powerful shortcodes to display templates and categories:

#### [taskip_templates]
Displays a grid of templates with optional filtering.

**Parameters:**
- `type` - Filter by template type slug (comma-separated for multiple types)
- `industry` - Filter by industry slug (comma-separated for multiple industries)
- `limit` - Number of templates to display (default: 12)
- `columns` - Number of columns in the grid (default: 3)
- `orderby` - Order by parameter (default: date)
- `order` - Order direction (default: DESC)

**Example:**

#### [taskip_template_categories]
Displays a list of template categories (types).

**Parameters:**
- `orderby` - Order by parameter (default: name)
- `order` - Order direction (default: ASC)
- `hide_empty` - Hide empty categories (default: 1)
- `show_count` - Show template count (default: 1)

**Example:**

#### [taskip_template_industries]
Displays a list of template industries.

**Parameters:**
- `orderby` - Order by parameter (default: name)
- `order` - Order direction (default: ASC)
- `hide_empty` - Hide empty industries (default: 1)
- `show_count` - Show template count (default: 1)

**Example:**

## Requirements

- WordPress 5.0 or higher
- PHP 7.4 or higher
- MySQL 5.6 or higher

## Frequently Asked Questions

**Q: Can I customize the template display layout?**
A: Yes, you can override the template files by copying them from the plugin's `templates` directory to your theme's directory.

**Q: Is the search feature real-time?**
A: Yes, the search feature uses Ajax with a 500ms debounce for optimal performance.

**Q: Can I add custom template categories?**
A: Yes, you can add custom template types and industries through the WordPress admin interface.

## Support

For support, please visit:
- [Documentation](https://taskip.net/docs)
- [Support Forum](https://taskip.net/support-ticket/)
- [Contact Us](https://taskip.net/contact/)

## Changelog

### 1.0.0
- Initial release
- Template post type implementation
- Custom taxonomies for types and industries
- Ajax search functionality
- Responsive template grid
- Preview functionality

### 1.0.1
- Added search debounce functionality
- Improved loading states
- Enhanced mobile responsiveness
- Bug fixes and performance improvements

## License

This plugin is licensed under the GPL v2 or later.

## Credits

Developed by [Taskip](https://taskip.net)

## Contributing
- [Taskip](https://taskip.net)
- [Sharifur](https://github.com/sharifur)


We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

For more information, visit [Taskip Templates Library](https://taskip.net/templates/)