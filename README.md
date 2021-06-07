# dl-data-samples
This repository is a small set of test data for use with the Cambridge Digital Library Platform.

It contains the following:

Source data (before processing)
 - TEI data
 - TIFF images (blank samples) [TODO]
 - JSON data for collections
 - HTML / images for website pages
 
 Processed Data (suitable for using directly with the cudl-viewer)
 - JSON data for items
 - HTML / images for website pages
 - Database snapshot SQL 
 
## Item file names

Item file names require a specific format.  e.g: MS-ADD-00001 containing three parts.

**MS** - This is a two letter code for e.g. MS: Manuscript or PR: Printed work.  Can be any two letters.

**ADD** - This is alphabetic code [a-zA-Z] indicating a grouping, e.g. ADD: Additional works, or GEOGRAPHY etc.

**00001** - This is the part that indicates the individual item (e.g. an individual book). This can be any combination of 
letters or numbers and can contain a - [A-Za-z0-9-].  It should end in a - then a 5 digit numeric number.  
E.g. TEST-ITEM-00001, HISTORY-OF-NEW-MUSEUMS-00002  

Parts are separated with a - character.

