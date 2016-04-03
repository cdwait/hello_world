
[Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
#Elements of Quality Assurance
##Automated Validation
* epubcheck
  * Oxygen can be loaded with epubcheck
* Verification is QA
##Retailer requirements
|Apple     |Kindle     |Kobo     |
|--------|-----------|--------|
|Bookasset Guide | Max: 650 megs|Spec is on Github|
|Links or references to other retailers will not get your book rejected|KDP upload max size: 50MB 'Kindlegen will double size'|EPUBCHECK not required but recommended|
|Include TOC, Cover, Start Location in "landmarks" EPUB3(guide) EPUB2|Max recommended image size: *5mb*|NCX/Nav auto-created|
|Supports audio/video (no fallbacks)|CSS is sometimes ignored|Font obfuscation not supported|
|Imnages shd. be smaller than 4 million px.|Javascript not supported|Audio/Video sometimes supported, use fallbacks|
|No more than 10mb per HTML file|NO postscript type fonts. Use OTF with Truetype definitions|Tables over 4 columns wide will cause problems (4 kindle as well)|
|Image optimization recommends RGB|Image scaling, use percents on one side, H or W||
||Media:Mobi7 format only||
