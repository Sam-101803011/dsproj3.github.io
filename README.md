# School Management System
---
## screenshots
### Homepage

## Flowchart 
![image](https://user-images.githubusercontent.com/90992662/142754096-54417e73-2bea-42f3-89c0-e705522b345e.png)

## Functions
![image](https://user-images.githubusercontent.com/90992662/142754170-1cd87f05-8b5f-4a58-a246-eafd5aa83695.png)
![image](https://user-images.githubusercontent.com/90992662/142754235-32145126-4863-45a5-adb2-60cba00ff83b.png)

### Teacher
First the teacher will apply for job,if he/she gets selected there accounts will be made and approved by the admin, after approval only teacher can access their dashboard.
After account approval by admin, teacher can take attendance of any class and view their attendance later.
Teacher can also publish/announce notice to student like submission of assignments.
![image](https://user-images.githubusercontent.com/90992662/142754317-429488eb-fd80-40be-bcc4-f8ae5b2caee8.png)
![image](https://user-images.githubusercontent.com/90992662/142754363-e27c2974-954d-427f-a808-0463ae947324.png)
![image](https://user-images.githubusercontent.com/90992662/142754376-be8cdf77-267b-4ca0-a17b-b291390c01ab.png)


## Student
First student will take admission/signup.
When their account is approved by admin, only then the student can access their dashboard.
After account approval by admin the student can view their details like attendance.
Student can't view attendance of other student.
Student can't announce, they can only view.
![image](https://user-images.githubusercontent.com/90992662/142754397-cf77a456-bdeb-4f0b-8500-1fae2c345861.png)
![image](https://user-images.githubusercontent.com/90992662/142754416-db81afb1-9ca5-44b9-9308-c82b338c9f30.png)


### Admin
First admin will signup for a account.
After login they can see how many student/teacher wants to get job/admission in their school.
They can approve or delete/cancel the request.
They can update any student/teacher details.
Admin can announce notice also.
![image](https://user-images.githubusercontent.com/90992662/142754262-2c1980b4-665f-4e89-8c1d-714b2031e25c.png)
![image](https://user-images.githubusercontent.com/90992662/142754276-e8df8a41-3d66-4d74-9dbd-77ff4a45ef41.png)
![image](https://user-images.githubusercontent.com/90992662/142754310-2c7e6470-c1be-45d3-9b45-6c2300a00328.png)



## Drawbacks
- On update page of teacher/student you must have to update password.
- Anyone can become Admin

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to gmail through host email id in your browser and open following link and turn it ON
```
https://myaccount.google.com/lesssecureapps
```

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.
