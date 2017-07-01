Introduction
------------

cmdtypist is a programmer oriented terminal typing tutor designed to work 
on the gnome-terminal, xterm and uxterm and others written in c. It consists
true programming lessons, so the user can type and learn at the same time.

License
-------

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

General Features
----------------

*Extremely fast, never again type faster than your type tutor!!!
*Has lessons for non programmers and c,c++,java/android programmers
*An accurate speed algorithm in character per minute (CPM) and an approximate
in word per minute WPM(accuracy -+0.35)
*Terminal is manipulated to print green a correct character and red a wrong
character
*Keeps a record of the number of wrong and correct characters
*Creates a text file to keep a account of the user speed in details(date,
numer of errors, speed in CPM and WPM and time elapsed) for each session.


Command Line Features
---------------------

-The user can choose to type in random mode where a random block is each 
session is chosen from selected lesson.
-And in standard mode, the user types chronologically as the lesson is in
the lesson file. 
-The user can chose to modify any lesson in the lesson file easily.
-For a user who will not love to modify the lesson file, a my_own.txt file
is available for the user to paste his text file he wants to type.

NOTE: Text file should contain only ascii 7 bits characters. For this reason,
user text may some times look absurd when contains extended ascii characters 
since program has a function to ignore such characters.
-User also can choose to receive a beep for any wrong character typed (may
not work on all terminals)
-Program has the ability to remember all past settings.
-Terminal is manipulated so a user can erase characters right to the beginning
of the session line(timing reset) For each wrong character erased, number of 
errors is decremented by one.
-User session timing starts only when he types a first character (wrong or 
correct)
-If the user erases to the beginning of the session, time is reset to zero
and starts only as described above.
-The last line of each lesson session is marked blue, so user is aware and 
can take time to review speed details befor estarting the following lesson.




