# regex-samples
complete source of useful regex patterns for using in javascript,php,....

1-## persian data sample :)
 
^(140[0123]{1}|13[0-9]{2}|[6-9]{2})[-/\s](0?[1-9]|1[012])[-/\s](0?[1-9]|[12][0-9]|3[01])$

hints :

-### this sample can accept data with (-) ,(/) ,(space) separators.
-### 1300 to 1403 for years
-### 01 to 12 or 1 to 12 for month
-### 01 to 31 or 1 to 31 for days
