# Batch Function Library

## Table of Contents

* [About](#about)
* [Synopsis](#synopsis)
* [Index of Functions](#index-of-functions)
** [Date and Time Functions](#date-and-time-functions)
** [File and Directory Functions](#file-and-directory-functions)
** [Network Functions](#network-functions)
** [System Functions](#system-functions)
* [Revisions](#revisions)
* [Copyright and License](#copyright-and-license)

## About<a name="about"></a>

Originally conceived in 2002 as a web based collection of date and time conversion functions, the library now also includes file, network and system functions. The library is no longer actively developed and his now archived on Github for prosperity.

## Synopsis<a name="synopsis"></a>

## Index of Functions<a name="index-of-functions"></a>

### Date and Time Functions<a name="date-and-time-functions"></a>

Function | Description
DateToDays | Converts a calendar date to the number of days elapsed since 1970-01-01
DateToDOW | Returns the day of week number for a given calendar date
DateToMins | Converts a calendar date to the number of minutes elapsed since 1970-01-01 00:00
DateToMJD | Converts a UTC date to a Modified Julian Day
DateToOrdinal | Returns an ordinal date from a calendar date as described by ISO 8601
DateToSecs | Converts a calendar date to the number of seconds elapsed since 1970-01-01 00:00:00
DateToWeek | Returns an ISO 8601 Week date from a calendar date
DayName | Returns the name of the day of week from the day of week number
DayNumber | Returns the number of the day of week from the day of week name
DaysToDate | Converts the number of days elapsed since 1970-01-01 to a calendar date
GetDate | Returns the local system date
GetTime | Returns the local system time
MinsToDate | Converts the number of minutes elapsed since 1970-01-01 00:00 to a calendar date and time
MJDToDate | Converts a Modified Julian Day to a UTC date
MonthName | Returns the name of month from the month number
MonthNumber | Returns the number of month from a month name
OrdinalToDate | Returns a calendar date from an ISO 8601 Ordinal date
SecsToDate | Converts the number of seconds elapsed since 1970-01-01 00:00:00 to a calendar date and time
WeekToDate | Returns a calendar date from an ISO 8601 Week date

### File and Directory Functions<a name="file-and-directory-functions"></a>

Function | Description
FileSizeComp | Compares the size of a specified file
GetDirStats | Returns the number of files, subdirectories and total size of a specified directory
IsDirEmpty | Determines if the specified directory is empty
IsInPath | Determines if the specified files are in the current directory or in a directory listed in the path statement

### Network Functions<a name="network-functions"></a>

Function | Description
GetDG | Returns the default gateway
GetIP | Returns the IP address of the primary adapter
GetMAC | Returns the MAC address of the primary adapter
GetNA | Returns the network address of the primary adapter
GetSM | Returns the subnet mask of the primary adapter

### System Functions<a name="system-functions"></a>

Function | Description
GetOS | Returns the operating system version
IsRunning | Determines if the specified service is running
Sleep | Suspends execution of the current batch file for a specified interval
Timer | Returns the number of elapsed seconds since the function was last called and first called
Uptime | Returns the elapsed days, hours, minutes and seconds since the system booted

## Copyright and License<a name="copyright-and-license"></a>

Code and documentation copyright 2002-2016 Ritchie Lawrence. Code released under [MIT License](https://github.com/ritchielawrence/mtee/blob/master/LICENSE.txt)
