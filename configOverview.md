# App config

The app config is located at `app/config/app.php`. These options control core application functionality.

## compile_container
Control whether or not the container is compiled.
- Environment Variable: `COMPILE_CONTAINER`
   - Possible Values: `false` or `<unset>`
   - Default Value: `<unset>`

## date_format
The format used for rendering dates in the application views.
- Environment Variable: `DATE_FORMAT`
   - Possible Values: [See possible values](../app/translations)
   - Default Value: `Y-m-d H:i:s`

## debug
Enable application debugging and display error messages.
- Environment Variable: `APP_DEBUG`
   - Possible Values: `true` or `false`
   - Default Value: `false`

## display_readmes
Parse and render `README` files on the page.
- Environment Variable: `DISPLAY_READMES`
   - Possible Values: `true` or `false`
   - Default Value: `true`

## google_analytics_id
Your Google analytics tracking ID.
- Environment Variable: `GOOGLE_ANALYTICS_ID`
   - Possible Values: A string in the format of `UA-123456789-0` or `false` to disable
   - Default Value: `false`

## hidden_files_list
File containing hidden file definitions.
- Environment Variable: `HIDDEN_FILES_LIST`
   - Possible Values: A path (string) to a file
   - Default Value: `.hidden`

## hidden_files
Array of hidden file definitions.
- Environment Variable: `HIDDEN_FILES`
   - Possible Values: An array of paths (strings)
   - Default Value: `[]` (an empty array)

## hide_app_files
Hide application specific files/directories.
- Environment Variable: `HIDE_APP_FILES`
   - Possible Values: `true` or `false`
   - Default Value: `true`

## hide_dot_files
Hide dot files/directories from the listing.
- Environment Variable: `HIDE_DOT_FILES`
   - Possible Values: `true` or `false`
   - Default Value: `true`

## hide_vcs_files
Hide the files Version Control Systems use to store their metadata.
- Environment Variable: `HIDE_VCS_FILES`
   - Possible Values: `true` or `false`
   - Default Value: `true`

## home_text
Text of the `home` link in the navigation breadcrumbs.
- Environment Variable: `HOME_TEXT`
   - Possible Values: Any string
   - Default Value: `null`

## language
The application's interface language.
- Environment Variable: `APP_LANGUAGE`
   - Possible Values: [See possible values](../app/translations)
   - Default Value: `en` (English)

## matomo_analytics_site_id
Your Matomo analytics site ID.
- Environment Variable: `MATOMO_ANALYTICS_SITE_ID`
   - Possible Values: A Matomo analytics site ID (string)
   - Default Value: `false`

## matomo_analytics_url
Your Matomo analytics URL.
- Environment Variable: `MATOMO_ANALYTICS_URL`
   - Possible Values: A Matomo analytics URL (string)
   - Default Value: `false`

## max_hash_size
The maximum file size that can be hashed.
- Environment Variable: `MAX_HASH_SIZE`
   - Possible Values: Any positive integer `0` - `9223372036854775807` ([`PHP_INT_MAX`](https://www.php.net/manual/en/reserved.constants.php#constant.php-int-max))
   - Default Value: `1000000000` (1 GB)

## meta_description
Meta tag description text.
- Environment Variable: `META_DESCRIPTION`
   - Possible Values: Any string
   - Default Value: `Yet another Web Folder Listing, powered by Web Explorer.`

## readmes_first
Show READMEs before the file listing.
- Environment Variable: `READMES_FIRST`
   - Possible Values: `true` or `false`
   - Default Value: `false`

## reverse_sort
When enabled, reverses the order of files.
- Environment Variable: `REVERSE_SORT`
   - Possible Values: `true` or `false`
   - Default Value: `false`

## site_title
The title of your Web Folder Listing.
- Environment Variable: `SITE_TITLE`
   - Possible Values: Any string
   - Default Value: `Web Explorer`

## sort_order
Sorting order of files and folders.
- Environment Variable: `SORT_ORDER`
   - Possible Values: `type`, `natural`, `name`, `accessed`, `changed`, `modified`, `<anonymous function>`
   - Default Value: `type`

## timezone
Time zone used for date formatting.
- Environment Variable: `TIMEZONE`
   - Possible Values: For a list of supported time zones see: [https://www.php.net/manual/en/timezones.php](https://www.php.net/manual/en/timezones.php).
   - Default Value: The server's timezone

## zip_downloads
Enable downloading of directories as a zip archive.
- Environment Variable: `ZIP_DOWNLOADS`
   - Possible Values: `true` or `false`
   - Default Value: `true`
