# Plugin Name

## Setup

There's some required associated plugins and theme components for this to work
- You need to have the "[Topic Thumbnails](https://meta.discourse.org/t/topic-list-thumbnails-theme-component/150602)" theme component installed and include it on your discourse themes.

### Admin settings

- discourse table gallery enabled: set to true to enable table gallery plugin
- rstudio composer gallery template category: add table gallery category to set up the form for creating topics
- table gallery categories: add table gallery category

### Customise settings

Topic Thumbnails - default should be none, table gallery category should be added to grid

Custom Banners - for allowing specific banners on the category page when filtered by enterprise tag, add another custom banner with `"tag": "enterprise"` in the JSON.
