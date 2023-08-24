## Description
Plugin extends JetSmartFilters functionality. It allows to search posts by post Title in the Search filter.
Plugin not depends on Search by control from filter options - it will allow to search also by post title with both variants - Default WordPress search and By Custom Field (from Query Variable).

Dy default will search by exact match. If you want to search by partial match,  add this code into the end of functions.php file of your active theme:

```php
add_filter( 'jet-smart-filters-search-by-title/exact-match', '__return_false' );
```

## How to use
- Download, install and activate plugin;
- Plugin not requires any configuration - after activation all active Search filters starts trying to search posts also by post title in Default Wordpress search.
- If you want to search by post title in 'By Custom Field (from Query Variable)', just enter 'post_title' (without quotes).


## Source

- https://github.com/MjHead/jet-smart-filters-search-by-id 
