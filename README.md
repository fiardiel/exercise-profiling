## Screenshots

`/all_student_name`
![All student name using jmeter GUI](assets/all_student_name_gui.png)
![All student name using jmeter CLI](assets/all_student_name_cli.png)

`/highest_gpa`
![Highest GPA using jmeter GUI](assets/highest_gpa_gui.png)
![Highest GPA using jmeter CLI](assets/highest_gpa_cli.png)

## Optimization results
    
`/highest_gpa`
![Highest GPA using jmeter CLI](assets/highest_gpa_opt.png)

`/all_student_name`
![All student name using jmeter CLI](assets/all_student_name_opt.png)
 
I didn't do any optimization on the highest_gpa part as it was already the most appropriate way to 
find the maximum of an array. For the all student name, I changed the implementation of using a list into
using a map since we have a key of student (id) and can have many classes. We can see that the optimization is
almost 50%