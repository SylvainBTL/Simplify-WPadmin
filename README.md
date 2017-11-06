![banner](https://github.com/SylvainBTL/Simplify-WPadmin/blob/master/banner.jpg)


# Simplify WPadmin

**Simplify WPadmin** it's clean and soft wordpress admin interface.

## Installation

###  1 - Function.php

Add this code in your fonction.php

```
function admin_css() {

$admin_handle = 'admin_css';
$admin_stylesheet = get_template_directory_uri() . '/admin/admin.css';

wp_enqueue_style( $admin_handle, $admin_stylesheet );
}
add_action('admin_print_styles', 'admin_css', 11 );

```


### 2 - Stylesheet

Create /admin/ folder in your main parent theme and place admin.css into.


## Have fun

License: GPLv2 or later /
License URI: http://www.gnu.org/licenses/gpl-2.0.html /
Wordpress: 4.8.3 

