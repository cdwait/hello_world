
[Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
#Elements of Quality Assurance 
_By Joshua Tallent_
*Disorderly and incomplete notes taken by Chris Wait*

__Main takeaways__
1. I need to improve my CSS reset
  *specifically regarding line-height
2. Should I be hacking small-caps?
3. Forget about the NOOK. It's doomed. 

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

__ereaders load books by HTML file, one chapter at a time, all images etc. included__

__Javascript: not supported. Don't even try.__

##What devices should I have?

1. IPAD
  * Support for many apps
    1. eBooks
    2. Kindle
    3. Kobo
    4. Nook
    5. Google
    6. Bluefire
2. Kindle Fire
3. Kindle Paperwhite
4. Android Tablet

##Device updates
  * Know what OS version and app version you're testing on
  * Test on older and newer versions

##Be aware of
* Conversion House limitations
* Default Style Sheets
* Styles for different genres
* Common conversion issues

##Build a QA checklist
1. Test on all targeted devices
2. Overview entire content
  * Content out of place?
  * Content missing?
  * Page breaks in correct places?
  * Inconsistent formatting?
 3. Metadata
   * Title
   * Author
   * ISBN
 4. Internal and external links work
 5. Unicode text
 6. Cover images
 7. Copyright page
 8. TOC
 9. Headings
 10. (Again) Formatting consistent
 11. Page #s (part of code)
 12. Text Color (ew)
 13. Images
 14. Footnotes
 15. Indices 
 16. Media & interactivity
 17. Accessibility
   * [BISM Quickstart Guide to Accessible Publishing](https://www.bisg.org/publications/bisg-quick-start-guide-accessible-publishing)

