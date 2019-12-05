# The Hidden Holy Grail for Gathering IRS 990 Data

***

This folder is a direct copy of jsfenfen's [990-xml-metadata](https://github.com/jsfenfen/990-xml-metadata/tree/4ad69cc0f68dedb1137ccae34c4c84f88295b0a9) repository. The work done by jsfenfen is truly praiseworthy. 

I'm dropping it here for the time being while I work on this project. Later, this directory will be converted into a proper subdirectory.

For now I just need this data to be readily accessable at all times until I say so. 

Also you can find more info [here](http://www.irsx.info/metadata/forms.html).

# What you will find in this Holy Treasure:

## `descriptions.csv` 

This holiest of -- ok, I'm done with that bit.... This file contains 6777 descriptions of fields used by the IRS. Some are still current. Some are no longer used. 

4  fields are used here: 
* `xpath` 
* `version_start`
* `version_end` 
* `description`

## `groups.csv` 

File contains 183 groups. Some are current. Some are no longer used.
 
10 fields are used here: 
* `parent_sked` (read as: Parent Schedule)
* `parent_sked_part` (Parent Schedule Part Number) 
* `ordering`
* `xpath`
* `db_name`  (database name)
* `line_number`
* `description`
* `headless` (this is an empty field. No idea what it is.)
* `version_start`
* `version_end`

## `line_numbers.csv` 

File contains 7154 lines.


Reminder to finish this when I have time...