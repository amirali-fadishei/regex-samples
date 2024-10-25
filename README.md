# regex-samples
complete source of useful regex patterns for using in javascript,php,....

## 1-persian date sample :)
 
`^(140[0123]{1}|13[0-9]{2}|[6-9]{2})[-/\s](0?[1-9]|1[012])[-/\s](0?[1-9]|[12][0-9]|3[01])$`

## hints :

#### - this sample can accept (-) ,(/) ,(space) separators.
#### - 1300 to 1403 for years.
#### - 01 to 12 or 1 to 12 for month.
#### - 01 to 31 or 1 to 31 for days.



## 2-persian Telephone number sample :)

`^0\d{2,3}\-\d{8}$`

## hints :

#### - "0" digit is necessary at beginning of the number due to the country legals.
#### - 2 or 3 digit number after "0" for province code.
#### - "-" character for separate pre-number and main number.
#### - 8 digit number at the end (main number).



## 3-Email(gmail,yahoo,host,...) sample :)

`^[\w\d]+([._-]?[\w\d]+)*@[\w\d]+([-]?[\w\d]+)*(\.[\w]{2,})+$`
