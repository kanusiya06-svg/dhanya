# dhanya
first enter the student details(task 1)
Columns:
Student_ID
Name
Department
Mark1 to Mark5
Attendance (%)
Proper table format-la data create pannen
next task 2
Total Marks → sum of add total 5 mark, to display the o/p formula: EXAMPLE =SUM(D2:H2) -ENTER 
Average → FORMULA(EG):=AVERAGE(D2:H2) -ENTER
average means =total mark  /count 
Marks Result →
Total ≥ 50 → PASS
Total < 50 → FAIL
SELECT THE  MARK 1 TO MARK 5 (COLUMN)
THE FORMULA:==IF(MIN(D2:H2)>=50,"PASS","FAIL")
its means less than 50 na its show fail and greater than 50 its show pass 
TASK 3:
TO CREATE A NEW MARK  
I  USE THIS IF CONDITION &SELECT THE MARK TO IMPORT THE FORMULA ,70 ABOVE NA "B" GRADE AND 85 ABOVE NA "A" GRADE ,50 ABOVE "C" OR "F" GRADE KUDUTHEN 
FORMULA: =IF(M2>=85,"A",IF(M2>=70,"B",IF(M2>=50,"C","F")))-ENTER 
TASK 4 
ITS TO CALCULATE THE ATTENDANCE 
 Attendance < 75% iruntha
 “Not Eligible” nu mark AGUM
 75 ABOVE IRUNTHA ITS SHOW ELIGIBLE 
 FORMULA:=IF(I2<75%,"Not Eligible","Eligible")
              |
            SELECT THE ATTENDANCE ROW 
Attendance eligibility  using IF condition
Task 5: Summary Sheet
Separate summary sheet TO CREATE THE COLUMN  :
Total number of students
Number of Pass students
Number of Fail students
Average Attendance
Top Scorer Name (highest total marks)
I)FIRST ITS TAKE THE TOTAL STUDENT 
ITS FIND THE TOTAL NUMBER OF STUDENT 
FORMULA :=COUNTA(SHEET1!A2:A10)-ENTER
                         |
                         ITS SELECT THE STUDENT_ID COLUMN
  II)Number of Pass students:
  TO FIND THE NO OF STUDENT PASS
  FORMULA:=COUNTIF(SHEET1!L2:L10,"PASS")
                            |
                            ITS  SELECT THE MARK RESULT(PASS/FAIL) COLUMN
                            ENTER
III)TO FIND THE NO OF FAIL STUDENT 
FORMULA:=COUNTIF(SHEET1!L2:L10,"FAIL")
                          |
                          ITS REPRESENT MEANS ITS SELECT THE MARK RESULT(FAIL/PASS) columns
                           ENTER AGAIN
 IV)Average Attendance
ITS LIKE 9 COLUMN  IRUKU ATTENDANCE ATHA ADD PANNUM NINE AALA DIVIDE PANNUM 
FORMULA:=AVERAGE(SHEET1!K2:K10)
                           |
                           ITS SELECT THE AVERAGE COLUMN
ENTER
ITS SHOW AVERAGE atendance
Top Scorer Name (highest total marks)
mark 1 and mark 5& total mark itha vachu topper student name o/p display pannalam
formula :=INDEX(Sheet1!B2:B10, MATCH(MAX(Sheet1!J2:J10), Sheet1!J2:J10, 0))
                          |                         |

                          select the student name    select the total marks 
                          enter 
                          its shows topper student name    
condition used

IF Function
 Used to apply conditions like Pass/Fail and Attendance eligibility.
 COUNTIF Function
 Used to count number of students who passed or failed based on condition.
 AVERAGE Function
  Used to calculate the average attendance of all students.
 INDEX Function
 Used to return the student name from a specific row.
 MATCH Function
 Used to find the position of the highest total marks.
 INDEX + MATCH (Together)
 Used to identify the top scorer name based on maximum total marks.
COUNTA Function
Used to count total number of students by counting non-empty cells.                          





