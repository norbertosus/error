Błąd typu E_ERROR został spowodowany w linii 34 pliku /home/host851510/domains/.../public_html/wp-content/plugins/google-listings-and-ads/src/Admin/BulkEdit/BulkEditInitializer.php. Komunikat błędu: Uncaught TypeError: Automattic\WooCommerce\GoogleListingsAndAds\Admin\BulkEdit\BulkEditInitializer::bulk_edit_hook(): Argument #2 ($post) must be of type WP_Post, null given, called in /home/host851510/domains/.../public_html/wp-includes/class-wp-hook.php on line 326 and defined in /home/host851510/domains/.../public_html/wp-content/plugins/google-listings-and-ads/src/Admin/BulkEdit/BulkEditInitializer.php:34
Stack trace:
#0 /home/host851510/domains/.../public_html/wp-includes/class-wp-hook.php(326): Automattic\WooCommerce\GoogleListingsAndAds\Admin\BulkEdit\BulkEditInitializer->bulk_edit_hook()
#1 /home/host851510/domains/.../public_html/wp-includes/class-wp-hook.php(348): WP_Hook->apply_filters()
#2 /home/host851510/domains/.../public_html/wp-includes/plugin.php(517): WP_Hook->do_action()
#3 /home/host851510/domains/.../public_html/wp-includes/post.php(4760): do_action()
#4 /home/host851510/domains/.../public_html/wp-admin/includes/post.php(753): wp_insert_post()
#5 /home/host851510/domains/.../public_html/wp-admin/post-new.php(66): get_default_post_to_edit()
#6 {main}
  thrown
