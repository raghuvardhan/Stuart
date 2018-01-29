  Technologies: 
  1.	Room Library (For database) 
  2.	Stetho (for debugging) 
  
  Activities:  
    1.	Attendance Activity: 
      a.	Aim:
        1.	Should take 3 output values: 
            Classes Held 
            Classes Attended 
            Desired Percentage 
        2.	Should display following information:  
            a.	Current Percentage 
            b.	No of classes required to attend 
      b.	Interfaces :  
        1.	Added 5 textboxes (editable). Added 5 textboxes (editable). Of them are for user Input (Classes Held, Classes Attended,                   Desired Percentage). 
        2 are for output (current attendance percentage, number of classes required to attend). 
        2.	Should add labels for boxes. 
      c.	Working:  
        1.	Calculating the output values based on the input using attendance formula. 
      d.	Issues: 
        1.	Showing wrong output values. Must be an issue with formula or type casting. 
   2. Reminder Activity: 	
      a. Aim: 
        1.Activity to add task reminders and remind them.It contains a add task button which opens a new dialog where you can give inputs. 	       2. It should take following input values: 
          a.	Title of task 
          b.	Time to reminder 
        2.	It will set a reminder (alarm ) and the task details on the interface. 
      b. Interfaces: 
        1. Created a task view for alertDialog with textbox(title), time picker and button to save. 	
        2.In the activity.xml, Added a table layout to display the tasks and a button to open dialog box. 
      c. Working: 	
        1. Takes the input from user in alertDialog and create a task object.
        2. Insert the task object in the database using task Dao. 
