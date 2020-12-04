# Coding-Shortcut

The number of digits in an Integer
int length = String.valueOf(number).length();
int length = (int) (Math.log10(number) + 1);

Making 2 digit day
string currentDay = currentDate.Day < 10 ? "0" + currentDate.Day.ToString() : currentDate.Day.ToString();
