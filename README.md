# SqlQueryStress
SQL query stress simulator created by Adam Machanic http://sqlblog.com/blogs/adam_machanic/archive/2016/01/04/sqlquerystress-the-source-code.aspx

## To-Do from Adam
-Fix bug where SQLQueryStress tends to crash after the Stop button is hit. Some variable, I guess, is not being properly reset.<p></p>
-Implement a better query editor. The control I used is bare bones to the max and does no one any favors.<p></p>
-Apparently there are some bugs around the statistics creation options not getting properly turned off when you turn them off.<p></p>
-Enable more than 200 simultaneous threads. This was just an arbitrary number and can be changed by simply modifying the appropriate<p></p> control. But perhaps there is a smarter way to come up with a maximum?<p></p>
-Implement support for saving of statistics and collected information, and reporting on that data, especially when the same test is run more than once.<p></p>
-Implement support for multiple test queries.

