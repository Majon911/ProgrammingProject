# ProgrammingProject

THE README.TXT FILE
Our project focuses on the problem of elevator use efficiency in different building. There is a csv input for files with two variables. The first one is time at which a waiting time is reported in one hour bins. The second variable is the reported waiting time for an elevator to come.
 
Application:
The both variables can be graphed in various ways and information about what time of the day the biggest problems with elevator efficiency occur. This can be used to help identify time periods when the problem occurs and by that the reason for which the flow of people around the building is so high. Then the problem can be tackled in various ways. A second application for the use of this program would be the energy optimization of those elevators. For example, if there is a small movement of people a few elevators can be shut down for some period to save energy.

Constraints:
This program required a csv file containing data which is shaped exactly in the way the program was made to read it. If you switch any columns or provide the data in a wrong format the program will NOT process it. When it comes to inference you can gain from the insights produced by the program they are also limited. Information given in the graphs can lead the user to different areas where they can search for a solution to a problem, but the program does not solve a problem itself. Other resources are necessary to do so.
 
List of functions:
open_csv() – this function opens .CSV and .TXT (read as .CSV) files with two variables “waiting time”, “hour of occurrence” and assigns them into variables within python: “hour” and “waiting_time”. 
