# RequiredNotiFire
RequiredNotiFire is the open source library. Used to apply the notifications fire in WordPress admin panel. If your theme used any plugin that is required. Used it to fire the notification.

## Used

```php
RequiredNotifire::make( __( 'Thanks for', 'add_text_domain' ) )
->plugin_check( 'example_plugin_slug' )
->desc( __( 'Example description to show in admin panel.', 'add_text_domain' ) )
->dismiss( true )
->icon( 'htt_patho_of_icon' ) // jpg, jpeg, png, gif
->icon_alt('icon_alt_tag_name')
->type('error') // error, warning, update
->css_color('#9b0a46');
