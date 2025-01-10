1.	Write a html program to accept Name of the College, Total number of students in the college, Total number of halls (range till 100). 


<!doctype html>
<html>
<head>
<title> College Data </title>
</head>
<body>
<h1> College Information Form</h1>
<form name="Clgform" method="post" action="process.php">
Name of the College :
<input type="text" name="clg_name">
<br> <br>
Total No. of Students :
<input type="number" name="stud_no" min=1>
<br> <br>
Total No. of Halls :
<input type="range" name="hall_no" min=1 max=100>
<br> <br>
<input type="submit" value="SUBMIT">
<input type="reset" value="RESET">
</form>
</body>
</html>


2.	Write a html program to accept Name of the Employee (cannot be blank), Email Id of the Employee, Salary (maximum 50000). The data should be sent to the server.


 
 


3.	Write a html program to create a form to accept Doctor's name, number of patients (maximum 20), Date of examining patients. 


<!doctype html>
<html>
<head>
<title> Hospital Data </title>
</head>
<body>
<h1> Doctor Information Form</h1>
<form name="docform" method="post" action="process.php">
Name of the Doctor :
<input type="text" name="doc_name" REQUIRED>
<br> <br>
No. of Patients :
<input type="number" name="patient_no" min=1 max=20>
<br> <br>
Date of Examination :
<input type="date" name="ex_date">
<br> <br>
<input type="submit" value="SUBMIT">
 
 



4.	Write a html program to create a form to accept Patient's name, his
mobile number and date of birth. Keep all fields compulsory. 


<!doctype html>
<html>
<head>
<title> Hospital Data </title>
</head>
<body>
<h1> Patient Information Form</h1>
<form name="docform" method="post" action="process.php">
Name of the Patient :
<input type="text" name="pat_name" REQUIRED>
<br> <br> Mobile No. :
<input type="number" name="pat_mobile" REQUIRED>
<br> <br> Date of Birth :
<input type="date" name="pat_date" REQUIRED>
<br> <br>
<input type="submit" value="SUBMIT">
<input type="reset" value="RESET">
</form>
</body>
</html>



5.	Write a html program to create a form to accept student's name, number of practicals he has completed and provide facility to upload his completion certificate. 
 
<!doctype html>
<html>
<head>
<title> Student Data </title>
</head>
<body>
<h1> Student Practical Information Form</h1>
<form name="studform" method="post" action="process.php">
Name of the Student :
<input type="text" name="stud_name" REQUIRED>
<br> <br>
No. of Practicals Completed :
<input type="number" name="practical_no" min=1>
<br> <br>
Upload Completion Certificate :
<input type="file" name="certificate">
<br> <br>
<input type="submit" value="SUBMIT">
<input type="reset" value="RESET">
</form>
</body>
</html>




6.	Write a html program to create a form to accept students roll no (in number format), Unit test marks (maximum 25 marks), Terminal exam marks (maximum 50 marks). Include the name of the Subject teacher and send the data to the server.


 
 


7.	Write a html program to accept Student ID (combination of alphabets
and numbers), date of joining, College name, percentage in previous class (in digits). The data should be sent to the server.
8.	Write a html program to enter Travel Details as follows : Name of the Hotel, Date of check-in, Number of members (compulsory field). The data should be sent to server.


9.	Write a html program to create registration form to accept name, mobile no., date of birth. The form should have register caption in the button to submit the data.


 
 


10.	Write a html program to create Registration Form to accept Name, Mobile no (with pattern restriction) and Date of Birth. The form should have REGISTER written on the button to submit the data.
11.	Write html program to accept Name of the hospital, Email Id of the hospital, Number of beds in the hospital. The data should be sent to the server.


<!doctype html>
<html>
<head>
<title> Hospital Data </title>
</head>
<body>
<h1> Hospital Information Form</h1>
<form name="hospitalform" method="post" action="process.php">
Name of the Hospital :
<input type="text" name="hosp_name">
<br> <br> Email Id. :
<input type="email" name="hosp_email">
<br> <br>
Number of beds in Hospital :
<input type="number" name="hosp_beds">
<br> <br>
<input type="submit" value="SUBMIT">
<input type="reset" value="RESET">
 
 


12.	Write a html program to accept following information from the user. 1) Name of the hospital 2) Email Id of the hospital 3) Number of beds in the hospital 4) Nature of the Hospital (Private or Government). The data
should be sent to the server.


13.	Write a html program to accept Email Id of the Hotel, Date of Foundation, Number of tables in hotel. The data should be sent to the server.


14.	Write html program to create a form to accept students roll no (in number format), Unit test marks(maximum 25 marks), Terminal exam marks (maximum 50 marks). Include the name of the Subject teacher and send the data to the server.


<!doctype html>
<html>
<head>
<title> Student Data </title>
</head>
<body>
<h1> Student Exam Marks Form</h1>
<form name="studform" method="post" action="process.php">
Student Roll No :
<input type="number" name="stud_roll" min=1>
<br> <br>
Unit Test Marks :
<input type="number" name="unit_test" min=0 max=25>
<br> <br>
Terminal Exam Marks :
<input type="number" name="unit_test" min=0 max=50>
<br> <br>
Name of the Subject Teacher :
 
 



15.	Write html program to accept student name, Date of birth(compulsory field) and attendance (in number form). Send the data to the server.


<!doctype html>
<html>
<head>
<title> Student Data </title>
</head>
<body>
<h1> Student Attendance Percentage </h1>
<form name="studform" method="post" action="process.php">
Student Name :
<input type="text" name="stud_name">
<br> <br> Date of Birth:
<input type="date" name="stud_dob" REQUIRED>
<br> <br>
Attendance Percentage :
<input type="number" name="stud_attd" min=0 max=100>
<br> <br>
<input type="submit" value="SUBMIT">
<input type="reset" value="RESET">
</form>
</body>
</html>
 
16.	Write a html program to display "Digital India" in Verdana font using internal CSS. Add any two sentences about Digital India below in orange color. 


<!doctype html>
<html>
<head>
<title> Digital India </title>
<style>
h1 { font-family : "Verdana"; } p { color : orange;	}
</style>
</head>
<body>
<h1> Digital India</h1>
<p> Digital India is a campaign launched by the Government of India to ensure that the Government's services are made
available to citizens electronically through improved online infrastructure and by increasing Internet connectivity. </p>

<p> It making the country digitally empowered in the field of technology. </p>

</body>
</html>


17.	Write a html program to display "Digital India" having underline using inline CSS. Add any two sentences about IT subject below having yellow color background for the text.


18.	Write a html program to display "Maharashtra State Board" in blue color and font size 30 pixels using internal CSS. Give background colour yellow for the web page.


 
 


19.	Write a html program to display State Government of India in red color and font size 30 pixels and align to the center. Give background color yellow for the webpage. Use External CSS.


20.	Write a html program to display Cyber Millennia having Arial font and dotted border. Add any two advantages in blue color text. Use internal CSS to achieve the same.


21.	Write a html program to display "Maharashtra State Board" in font size 40 pixels using internal CSS. Give background colour yellow for the same text.


 
 


22.	Write a html code to display Good Morning having bold effect and underline. Also display Welcome to our page centrally in 30 pixel font size. Use inline CSS to achieve the above.


23.	Write a html program to display Ecommerce having Arial font using inline CSS. Add an ordered list having any two advantages of it.


24.	Write a html program to display "Web designing" in italic format and having underline using internal CSS. Add any two sentences about web designing in green color.


 
25.	Write a html code to display scientist name Homi J Bhabha having text color blue, underling the same and align it to the center of the page using internal CSS.


26.	Write a html program to display SAVE WATER SAVE EARTH in blue color with dotted border and 30px font size. Add any two sentences about how to save water in a paragraph in green color. Use internal CSS to
achieve the same.


27.	Write html program to display Information Technology in bold format and Times New Roman font. Add any two sentences about IT subject
below in orange color. Use inline CSS.


28.	Write html program to two paragraphs and display first paragraph should have cyan background color and second should have yellow text color with blue background color.


29.	Write a html program to insert inline frame on web page. Use xyz html file as a source for inline frame. Size of inline frame should be 100x100
pixels.



 
30.	Write html program to insert inline frame on web page. Use xyz html file as a source for inline frame. Size of inline frame should be 300 x 300 pixels.







31.	Write a html program to create a list of 3 flowers in ordered list and list of 3 fruits in unordered list.


32.	Write a html code to display a list of any 4 author names in ordered list using relevant list tags (e.g. author P.L. Deshpande, Kusumagraj, Chetan Bhagat) in roman numbering I, II, III ….


33.	Write a html program to create an ordered list of Tea and Coffee and unordered list under Coffee as Black Coffee and cold Coffee.


34.	Write a html program to create an ordered list of Tea, Coffee and Milk and unordered list under Milk as Turmeric Milk and Hot Chocolate.
 
35.	Write a html program to create an ordered list of Waffles and Cake
Shake and add Orea and Salted Caramel in unordered listing under Cake Shake.


36.	Write a html program to create an unordered list having names of two students. Add in ordered list 2 subjects that they have selected in FYJC
below each of their names.

37.	Write a html program to create an ordered list of 3 courses (FYBCom, SYBCom, TYBCom) in Bhaktivedanta College and under each stream mention 3 subjects taught in Unordered listing.


38.	Write a html program to create an ordered list of 3 cities and under each city mention names of 3 banks in unordered list. Give heading as Metropolitan Banks.


39.	Write a html program to create an Ordered list having two streams
Commerce and Science. Under each stream enter 2 classes FYJC and SYJC in Unordered listing.


40.	Write html program to create an ordered list of 3 languages used for speaking and unordered list having 2 computer languages. 


 
 



41.	Write html program to display names of two friends in ordered list and also display their hobbies under their name in unordered list. 


 
42.	Write html program to create an unordered list having names of two students. Add ordered list of subjects they selected:




43.	Write a html program to create nested list having names of two students. Add ordered list of 3 subjects that they have selected under each name.
