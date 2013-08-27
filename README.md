WordPress-gSearch-plus
======================

Improves the WordPress search engine without messing with the database, sorts results by relevance, and more. Simple and clean!

gSearch Plus plugin improves WordPress' default mechanism by searching through custom taxonomies (including category and tags) and custom fields. It orders the results by relevance, calculating the search words hits through the title and content of each post. This plugin also includes a stopwords mechanism to remove the non-relevant words from the query, thus increasing the relevance of the results. Stopwords can be defined manually (using the WP admin) or by using the default files provided with the plugin package.

## Features

* Searches through all the posts, pages and custom post types, by title and content (AND query)
* Extends search to all custom taxonomies, category and tags (AND query)
* Extends search to custom fields (AND query)
* Sorts results by relevance
* Highlights searched terms (optional)
* Removes stopwords from search query
* Integrates the stopwords mechanism with Stella multi-language plugin, by removing the current language stopwords from the search query

Very easy to use and setup! No new database tables or complex configurations. gSearch Plus uses only WordPress' APIs and functions! Simple and Clean!

## Usage

1. Upload the `gsearch-plus` folder to the `/wp-content/plugins/` directory
2. Activate the **gSearch Plus** plugin through the 'Plugins' menu in WordPress
3. Configure the plugin by going to the **gSearch Plus** menu that appears in your *Settings* menu

That’s all! We hope that you like our plugin. Suggestions, questions and other feedback are welcome. [twitter: @luistinygod](http://twitter.com/luistinygod)

## License

The WordPress gSearch Plus is licensed under the GPL v2 or later.

> This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License, version 2, as 
published by the Free Software Foundation.

> This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

> You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA

## Changelog

### 1.1.6
* Revision and testing for WP 3.6

### 1.1.5
* Optimized queries to reduce needed memory

### 1.1.4
* Less strict when searching custom fields (LIKE compare)

### 1.1.3
* Corrects issue regarding spaces in the middle of searched terms

### 1.1.2
* Corrects issue regarding spaces on beginning and end of the search sentence.

### 1.1.1
* Minor corrections on jshighlight script

### 1.1.0
* New features: custom fields search & highlight searched terms. 
* Includes two new js: jscolor plugin and jshighlight

### 1.0.0
* Initial release. 
* No multisite compatibility. More to come shortly.

## Author Information

The WordPress gSearch Plus plugin was originally started and is maintained by [Luis Godinho](https://twitter.com/luistinygod) and it's part of [GOMO](http://www.gomo.pt/) portfolio.

The project is open-source and receives contributions from awesome WordPress Developers throughout the world.
