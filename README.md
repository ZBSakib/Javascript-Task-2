# Javascript-Task-2
1. Create a Javascript code, where you introduce class Student using class declaration. Student has following properties: Name, birth date, address, phone number. Student has following methods:
- print() - prints all properties values
- countAge() - counts age based on birth date. 

Use getters/setters to handle properties. Birth date must be instance of Javascript Date class.

2. Create previous task using "functional class pattern"-definition. There shouldn't be any getters and setters.

3. Add to first. Introduce class Grade, that contains following information: course, grade and date of passing the course. For Student class, introduce property that contains array of grades, which each are type Grade. Also for Student class add methods
- addGrade -adds new Grade object to table of grades
- printGrades - which prints all the grades of student (course, grade, date)

Use Javascripts Date class for passing course dates. Grade must be between 0 and 10.

4. Add to previous tasks Student class: Add getters goodStudent and passedCourses. goodStudent returns true if even one course is grade 5. passedCourses returns true if every courses grade is at least 1. Add method giveGradesScaled, which gives grades scaled to 0 to 5 ( 1 -2 => I, 3-4 => II, 5-6=>III, 7-8=>IV ja 9-10=>V).

Use Array classes some(), every() and map() -methods.
