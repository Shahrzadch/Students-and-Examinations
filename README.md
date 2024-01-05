**Students and Examinations**

There are three tables. The first one is Students where we have 2 fields of student_id and stundet_name. student_id is the primary key (column with unique values) for this table.
Each row of this table contains the ID and the name of one student in the school.
The second table is Subjects with one field of subject_name which is the primary key (column with unique values) for this table.
Each row of this table contains the name of one subject in the school.
The third one is Examination with two fields of student_id and subject_name.
There is no primary key (column with unique values) for this table. It may contain duplicates.
Each student from the Students table takes every course from the Subjects table.
Each row of this table indicates that a student with ID student_id attended the exam of subject_name.
 

Write a solution to find the number of times each student attended each exam.

Return the result table ordered by student_id and subject_name.
