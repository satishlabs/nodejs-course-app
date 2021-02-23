# nodejs-course-app

1) Create the Database called jlcdb
2) Create the Collection called mycourses
3) Insert 5 Documents into mycourses collection as follows
      [{
      "courseId": "C-101",
      "courseName": "Java Full Stack Course",
      "duration": "500 Hrs",
      "trainer": "Srinivas Dande",
      "enrollments": 25000
      },
      {
      "courseId": "C-102",
      "courseName": "Spring Boot Course",
      "duration": "45 Hrs",
      "trainer": "Srinivas Dande",
      "enrollments": 200
      },
      {
      "courseId": "C-103",
      "courseName": "Spring MicroServices Course",
      "duration": "45 Hrs",
      "trainer": "Srinivas Dande",
      "enrollments": 200
      },
      {
      "courseId": "C-104",
      "courseName": "Angular Course",
      "duration": "45 Hrs",
      "trainer": "Srinivas Dande",
      "enrollments": 200
      },
      {
      "courseId": "C-105",
      "courseName": "React Course",
      "duration": "45 Hrs",
      "trainer": "Srinivas Dande",
      "enrollments": 50
      }] 
      
   4) Start the app
        npm run server
   5)Hit the URL:
       http://localhost:5500/myapi/mycourse/C-102
       http://localhost:5500/myapi/mycourses
