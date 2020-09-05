# Linux Commands
## 1. Basic Linux Commands
1. echo sth = print(sth): sth could be plain text with "", or variable.
2. cal
   * default: calendar of current month
   * -y: calendar of current year
   * year (input) / -y (option) year (input): full calendar of selected year
   * month year: calendar of chose month and year
   * cal -A / -B n month year: both selected month in that year and n months after / before the selection
3. date: 
   * default: full date time information at your current location
   * -u / --universal: UTC time
4. clear: clear the teminal screen
5. history: all typed commands
   * use !n to choose the nth commands you used before
   * !! the most recent used commands
6. man
    * -k commandName: search for a command in manual
        * Left side: the name of certain manual pages with section number in parentheses ()
        * Right side: synopsis about the actual page
    * sectionNum commandName: get the command manual page 
        * If the command is in section one, the sectionNum could be omitted
7. which [-a] filename1 (filename2 ...)
        