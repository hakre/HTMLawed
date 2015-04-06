# htmLawed

PHP code to purify & filter HTML

 * make HTML markup in text secure and standard-compliant
 * process text for use in HTML, XHTML or XML documents
 * restrict HTML elements, attributes or URL protocols using black- or white-lists
 * balance tags, check element nesting, transform deprecated attributes and tags, make relative URLs absolute, etc.
 * **fast, highly customizable, well-documented**
 * single, 48 kb file
 * simple HTML Tidy alternative
 * free and licensed under LGPL v3 and GPL v2+
 * use to filter, secure & sanitize HTML in blog comments or forum posts, generate XML-compatible feed items from web-page excerpts, convert HTML to XHTML, pretty-print HTML, scrape web-pages, reduce spam, remove XSS code, etc.

Read more on the [official *htmLawed* homepage](http://www.bioinformatics.org/phplabware/internal_utilities/htmLawed/). 

## Why a fork?

This git repository tracks changes from the upstream project to allow installation via composer and packagist because 
the original project doesn't offer compatible and publicly available version control.

The tracking works highly automated. Timestamps are backported for each release, and releases are tagged according to 
their original versions. This might produce problems for some versions with packagist. We'll see.
