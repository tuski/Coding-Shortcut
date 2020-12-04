# Coding-Shortcut

The number of digits in an Integer <br>
int length = String.valueOf(number).length(); <br>
int length = (int) (Math.log10(number) + 1);

Making 2 digit day <br>
string currentDay = currentDate.Day < 10 ? "0" + currentDate.Day.ToString() : currentDate.Day.ToString();
