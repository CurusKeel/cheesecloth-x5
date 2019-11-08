# cheesecloth-x5
Programming project (?) for CS 400. Supposedly this is a LMS, but who can say for sure?

Team members:
* Curus Keel (@CurusKeel)
* Drew Coe (@Dr-ewC)
* Kevin Fang (@kfang22)
* Ryan Brown (@rjbrown38)

Problem: Managing students and their progress within classes is itself a challenging problem, especially as class sizes get larger. It is already difficult enough to grade students based on their work, hard enough that it should be persistent for your courses.

Primary stakeholders: Instructors that need to add, view, edit, remove, etc. a student's profile.

Graphical User interface: Instructors will be able to type a name of a student and will get back information of the student.
Instructors will also be able to perform searches about how many students in his/her class have As, ABs, Bs, etc. as well as 
the grades for specific assignments. Instructor will also be able to check attendance for each student and search which students didn’t come to a specific lecture. 

Data: Data of the student will include grade for the class, grades for specific assignments, details of specific assignments, student year, attendance, etc. A hash table will be used to organize the students and will use more hash tables to organize specific data on students such as attendance and grades for specific assignments. Each lecture number will have its own unique list of students and student profiles.
