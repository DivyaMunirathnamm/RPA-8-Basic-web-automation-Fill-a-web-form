# RPA-8-Basic-web-automation-Fill-a-web-form
# NAME:DIVYA M
# REGISTER NUMBER:212223040043
# AIM:
To create a UiPath workflow that automates the process of filling out a basic contact form on a website and submits the form using Web Automation techniques.

# ALGORITHM:
# Step 1:
Launch the Browser Open UiPath Studio and create a new project called WebFormAutomation. Drag and drop the Use Application/Browser activity. Indicate the browser window or enter the form URL manually in the Application Path: https://form.jotform.com/242550815060449

# Step 2:
Fill Form Fields Inside the Use Application/Browser, add multiple Type Into activities for each field.

# Example:
Field Type Into Value First Name "DHARUNYADEVI", Last Name "S", Email "dharunyadevi2006@gmail.com", Message "Welcome to the world of robotic process automation". Use Click Before Typing and Activate options in Properties for accuracy.

# Step 3:
Select Dropdown (Optional) Use the Select Item activity to choose a state or country from a dropdown if present.

# Step 4:
Submit the Form Use a Click activity to click the Submit or Send button on the form.

# Step 5:
Add Delay (Optional) Add a Delay activity if the form takes time to load or submit.

# PROGRAM:
<img width="1920" height="1080" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/ad8deafb-6011-4708-9e1d-eb9f0370ac3e" />

<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/a50e7003-d7cf-4db1-8082-9ed8cb551cc4" />

# OUTPUT:
<img width="1919" height="951" alt="Screenshot 2025-10-04 140946" src="https://github.com/user-attachments/assets/4f94099b-6e97-4d73-a522-a21e2a079a06" />


# RESULT:
UiPath successfully automates form-filling tasks in a browser and submits a web-based contact form using Web Automation techniques.
