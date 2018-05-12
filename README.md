Bob Cole's Calendar Picker (tweaked by Mikey)
This will only work on unix (linux/macos), and not ios or windows, because it relies on the unix "cal" command.  I have not tried it on android.


v. 1.0.1 05/12/18
• Versioning/update per Mikey
• Changed "cal" to "cal -h" b/c "cal" will hilite the current day in the current month, which will hose LC's text (the hilite doesn't go well to plain text)
• Strip the spaces and cr's off the end of the calendar.  Under some circumstances, Bob's code would interpret these as 0's.
• Extended year range manually to 2025
• Added notes
• Expanded tab stops, calendar field, and moved other fields (LC9 rendering changes cause it to be unreadable)



From the stack script:
## Author : Bob Cole, USA Missouri
## bobcole@earthlink.net
## to be used freely
/** Stack Script
*
*This stack is a sample of how to use the 
*unix shell to get a monthly calendar
*and the mouseText function to pick a day
*\author Bob Cole
*\date February 25, 2010
*\version 1.0
*\note USA, Missouri
*
*/
