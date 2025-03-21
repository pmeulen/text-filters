OSX Text Filters for Bare Bones' BBEdit and TextWrangler
========================================================

These are Text filters that are intended to be used from the [Bare Bones](https://www.barebones.com/) text editors
BBedit (payed) and Text Wrangler (free). 
But these filters can be used from any shell as they receive their input via stdin and output the result on stdout.

Installation
------------

Put the filters in `~/Library/Application Support/BBEdit/Text Filters/` or `~/Library/Application Support/TextWrangler/Text Filters/`, 
depending on the editor you are using. Make sure that they are executable. The filters are now available in the "Text" -> "Apply Text Filter" menu.
And in the Filters Palette (Window -> Palettes -> Text Filters).

The filters use different shell commands that are not installed by default on macOS. Install them via e.g.
   [Macports](https://www.macports.org/) or [Homebrew](https://brew.sh/). The shell commands must be in your path. The commands used are:
  - `php` (used by many filters)
  - `openssl` (for certificate / ASN.1 filters)
  - `jq` (for Format JSON)
  - `xmllint` (for Format XML)

Enjoy!