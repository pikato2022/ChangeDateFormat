# ChangeDateFormat C# Solution (www.hackerrank.com) 
An application that you are implementing requires multiple date formats to be transformed into one common date format.

Implement the function ChangeDateFormat which accepts a list of strings, representing dates, and returns a new list with 
each date in the format YYYYMMDD. All incoming dates will be valid dates, but only those in one of the following formats: YYYY/MM/DD,
DD/MM/YYYY, and MM-DD-YYYY should be included in the returned list, where YYYY, MM, and DD are numbers representing year,
month, and day.

For example, ChangeDateFormat(newList{"2010/03/30","15/12/2016","11-15-2012","20130720"}); should return the list
{"20130330", "20161215","20121115"}.
