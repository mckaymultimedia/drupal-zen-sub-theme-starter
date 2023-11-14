# drupal-zen-sub-theme-starter
 
Befor using the sub-theme, make sure you have Zen base theme installed. You can download it from the Drupal.org website or use Composer to add it to your Drupal project. Ensure that the Zen base theme is located in the themes/contrib directory of your Drupal installation.

Enable the Sub-theme:

Go to the Drupal admin interface and navigate to "Appearance" (admin/appearance). You should see your sub-theme listed under "Disabled Themes." Click the "Install and set as default" link to enable and set your sub-theme as the default theme.

Customize Your Sub-theme:

Now that your sub-theme is enabled, you can start customizing it to fit your design and functionality requirements. You can override templates, create custom regions, add or modify CSS and JavaScript files, and implement preprocess functions in your myzen_subtheme.theme file.

Clear Cache:

After making changes to your sub-theme files, it's a good practice to clear the Drupal cache to ensure that your changes take effect. You can do this via the Drupal admin interface or by running drush cr or drupal cache:rebuild commands from the command line.

Customize Zen Starterkit:

Zen provides starterkits to help you customize the theme further. You can find starterkits in the themes/contrib/zen/starterkits directory. Copy the desired starterkit (e.g., starterkit-basic) to your sub-theme directory and follow the provided instructions to configure it.