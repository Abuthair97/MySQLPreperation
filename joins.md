# JOINS Two Table based on some condition

- SYNTAX FOR `SELECT s.name ,b.name as batchName  FROM Student  s join Batch b on s.batch_id= b.id ;`
- SELF JOINING SYNTAX : `SELECT s1.name , s2.name from Student s1 join Student s2 on s1.buddy_Id = s2.id;`

