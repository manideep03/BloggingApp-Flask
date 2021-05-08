# BloggingApp-Flask
A simple end to end blogging application created using **flask** and **MySql**.

Users can register and login to website to write a blog. Viewers without login also.

## Set up
- Create a database named *flaskapp* in **MySql**
- Create tables named **users** and **articles**
- Change *MySql* credentials in ```app.py``` file (line : 13)
- Open command prompt and navigate to project folder and then run ***app.py***

  ```bash
  python app.py
  ```
  
 
- you can see that project is running on localhoat port number 5000, can acess through ```localhost:5000```

## Database
All tables codes are written in ```database.txt``` file.

class diagram

![database](https://github.com/manideep03/BloggingApp-Flask/blob/main/imgs/database_class.png)


## Results

Home page

![Home](https://github.com/manideep03/BloggingApp-Flask/blob/main/imgs/home.png)

Register page

![register](https://github.com/manideep03/BloggingApp-Flask/blob/main/imgs/register.png)

Login page

![login](https://github.com/manideep03/BloggingApp-Flask/blob/main/imgs/login.png)

User Dashboard
![dashboard](https://github.com/manideep03/BloggingApp-Flask/blob/main/imgs/dashboard.png)

Add blog
![add_article](https://github.com/manideep03/BloggingApp-Flask/blob/main/imgs/add_blog.png)

All Blogs 
![all_blogs](https://github.com/manideep03/BloggingApp-Flask/blob/main/imgs/all_blogs.png)
