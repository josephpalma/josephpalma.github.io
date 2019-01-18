---
layout: essay
type: essay
title: Java Class LocalDateTime
date: 2015-08-26
labels:
  - Software Engineering
  - Learning
---

Java Class LocalDateTime
By Joe Palma 

This class was developed and released in Java 8. It extends Object class and implements Temporal, TemporalAdjuster, ChronoLocalDateTime, and Serializable. This class outputs a date-time without a time-zone, such as:

2017-12-06T13:02:47.403

LocalDateTime is an object of type LocalDateTime that represents a date-time, viewed as year-month-day-hour-minute-second. Other date and time fields, such as day-of-year, day-of-week and week-of-year, can also be accessed with the built in methods. Time is represented to nanosecond precision. For example, the value "2017-12-06T13:02:47.403" can be stored in a LocalDateTime variable. This class does not compute a time-zone. It is just a description of the date, as used for birthdays, along with the local time as seen on a wall clock.

LocalDateTime has many built methods that allow for a wide range of processing of the LocalDateTime value. I will provide a short description of some of the methods used in my DateAndTimeExample class:
•	LocalDateTime  LocalDateTime.now();  returns the current date and time. Other parameters include :
o	(Clock clock)  gets current date time from specified time 
•	Boolean  equals(Object obj);  Checks if this date-time is equal to another date-time
•	String  format(DateTimeFormatter formatter);  Formats this date-time using the DateTimeFormatter class, import DateTimeFormatter to use
•	int  get(TemporalFeild field);  Gets the value of the this field as an int using the TemporalFeild class
•	int  getDayOfTheMonth();  Gets the day of the month field. Other parameters include :
o	(int week) gets week
o	(int day) gets day 
o	(int hour) gets hour
o	(int minute) gets minute
o	(int second)  gets second
•	Boolean  isAfter(ChronoLocalDateTime<?> other); Checks if this date-time is after the specified date-time other parameters include: 
o	isBefore() checks for all values before
o	isEqual() checks for all values equal to 


