**57-days-of-weblearning**

To be more accountable and stay on track, I am accepting 57 days of weblearning (mostly django).
Here I will upload glimse of code I had done in particular day with short information.

**For Detail-version of code you can look in this repo**
[**Code repo**](https://github.com/QuaackQuaack/learning-django)

**Day 1 of 57 days**
- *Today I learnt about Built-in user authentication system and create Login, Logout, Singup*
- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)
![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day1.jpg)

**Day 2 of 57 days**
- *Today I learnt about management of static file in production. In development phase, static files are served through local machine but at the time of production, we usually optimize the deliever of static files, with the help of different static files engine. Currently I am using Whitenoise. Also, I learnt about custom user model by adding own fields i.e ages .*
- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)
![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day2.jpg) 


**Day 3 of 57 days**
- *Today I learnt about concept of Application Programming Interface(API) and REpresentational State Transfer (REST) API.In short, REST API is a protocol that allows a developer to perform command or exchange data with a service over a network. Not only that, I learnt about setting basic homepage with links to Login, Logout and Signup Features without repeating myself to setup Urls everytime by hand (DRY) with the help of TemplateView*

- Book 
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)
  - **Links to learn about REST API**
    - [**r/learnprogramming**](https://www.reddit.com/r/learnprogramming/comments/apvqie/can_someone_please_explain_like_im_5what_a_rest/)
    - [**r/explainlikeimfive**](https://www.reddit.com/r/explainlikeimfive/comments/1fevr4/eli5_representational_state_transfer_rest_or/)

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day3.jpg) 


**Day 4 of 57 days**
- *Today I learnt about Testing philosophy of django and 80/20 rules, which states that 80% of consequences come from 20% of causes.There are two types of testing, unit testing and intregration testing . I am following Unit regression testing. Also I learn about bootstrap and made my news app abit clear with the help of django crispy forms.*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day4.png) 

**Day 5 of 57 days**
- *Today I learnt about setting Template to change password and using django console backend*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day5.png) 

**Day 6 of 57 days**
- *Today I learn about how web works.Short introduction about Cross-Origin Resource-Sharing(CORS) and Ajax. CORS is basically a HTTP header that allows a server to indicate any origin other than it's own from which a browser should permit loading. Ajax is set of web development technique on client-side to create synchronus web application. URL is made up of Scheme (https, http, ftp), hostname(www.abc.com), and path(/about/), note path is optional part. Not only that, TCP uses three-way handshakes to establish connection which is synchronization(SYN), SYN-ACK, Ackowledgemnt(ACK). There are also many HTTP verbs used in most of web work. To remember https verbs, we can compare them with CRUD: Create equals to POST, Read equals to GET, Update equals to PUT or PATCH and last DELETE which is same in both. Status-codes are another important codes use in web. There are many status codes, but mainly codes start with 2XX links to succes made by client, 3XX links to redirection, 4XX links to client side error and 5XX links to server error.*

- Resources
  - Books 
    - **Django for APIs**

**Day 7 of 57 days**
- *Today I setup templates for password reset with django built-in emailing system*
- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day7.png) 

**Day 8 of 57 Days**
- *Today I revise CRUD feature of django by making bloging app.*
- Resource my old code file

**Day 9 of 57 Days**
- *Today I setup my news web model with CRUD feature and also learnt about managing emails through built-in backend console of django and 3rd party application like Sendgrid. Not, only that, I learnt about customizing the reset password email with the help of source code provided in github.Mainly today, I just code which I had already learnt in chapter 6 with some customization with the help of bootstrap*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day9.png) 

**Day 10 of 57 Days**
- *Today I learn basic command of Javascript and it's history. Also breif about conditional loop in javascript*

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day10.png) 

**Day 10 of Day 57Days**
- *Today I learn about types of Javascript values i.e numers, strings, Booleans, and undefined values.Also, learn about short circuit and type coercion in Javascript.*

[Resource for Js](https://eloquentjavascript.net/index.html)

**Day 11 of Day 57 Days**
- *Sorry, missed yesterday portion, Today I learn many new topics mixins, method resolution system, authentication in django, authorization and also building comment section in django. I will explain them separatly in each session*
  - *Mixins,(Multiple inheritance).I am approaching class based view and in django making our code complex is quite wrong approach. SO, with the help of abstract of django I setuped LoginRequiredMixin, UserPassesTestMixin which checks whether the user is logged in while working on CRUD and sets loggedIn user as author of the blog respectively. This way we control authorization of data to authenticate person.* 
  - *Also, I setup comment feature in blog, which is quite hard to understand at first.But I will go throughly about things I am quite familier. We should use Mixins and View of GET and POST separate and then pass them to wrapper view to avoid conflict. So, we made different view for GET and POST of comment. Also, I learned about many to one relationship in foreignkey (made relationship between comments and article).* 
  - *One more thing about django, Class-based views are powerful and in django, templates are complied only once to increase performance so, we must load everything from beginning into the context.For this, I learned about get_context_data() that add information to a template by updating the context.*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day11.png) 
![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day11b.png)

**Day 12 of Day 57 Days**
- *Today, I learn about deployment process in django.There is difference outlook of our program in production and deployement level. I learn to balance our production and deployement through Environment varaibles.At first I setup Environment variable with the django-project called [Environs](https://github.com/sloria/environs#features). I created .env files which contains all my hidden files like SECRET_KEYS, DEBUG, DATABASES_URL.Also, I made .gitignore files.It allows me to ignore files bro version control and control them in local machine only.Also, I learn to create my own secret keys with python.As our site grows we also need to take care of static files.So I use whitenoise package and set my MIDDLEWARE, STATICFILES_STORAGE based on whitenoise.At, last I setup GUNICORN for WSGI and create requirement.txt file with pip freeze > requirements.txt.*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)
  - [**Documentation For Deployement List**](https://docs.djangoproject.com/en/4.2/howto/deployment/checklist/)

![Image](https://github.com/QuaackQuaack/57-days-of-weblearning/blob/main/image/day12.png) 

**Day 13 of Day 57**
- *Few days ago I learn about comment setup, but today I went in detail about how django automatically set raltionship between defined model. Also, django makes our work quite easier in Object Relational Mapping.For example in my current project I made two model comments and Article and comment model have ForeignKey refrencing Article model so, to access the respective comment about article django creates attribute 'comment_set'. Generally, this is called `FOO_set` where FOO is lowercased name of source model.Also, I learned about two type of inliner in web. StackedInliner and TabularInliner(my fav too). These inliner are used to show comments in admin panel in either stacked form or tabular form. To set Inliner we edit our code through in admin.py by making one separate class and register it with model.*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)
 
**Day 14 of Day 57**
- *Today I learn about how generic class based are setup and its pros over function based, like using mixins and to override specific module to obtain desire outcome.Also,I revised about separting GET and POST class from DetailView because to make clear seperation and make my code clear.but I am still not getting the concept of Docker*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)
  - [**Docker Intro**](https://youtu.be/aLipr7tTuA4)

**Day 15 of Day 57**
- *Yesterday I learned about managing version control and monolith way of making app so, I didn't commit about it because I want to make this repo about web. Today, I learned about CustomUser and migrations importance in django. I was unknown about order of migration and error occur while inconsistancy.About CustomUser, We make different AUTH_USER_MODEL and add Age field in SignUp with the help of AbstractUser.*

- Book
  - [**Django for beginner**](https://djangoforbeginners.com/introduction/)

**Day 16 of day 57**
- *today I learn basic syntax of docker and managing image,how it help us to perform microservice on a single piece without being worry about it requiremnt like version,OS.Now, I am sure about syntax but to grasp the pratical importance of it, I guess I need to learn in through working.I will try to work on some project that involves docker or use docker*

- Resource
  - [reddit](https://www.reddit.com/r/docker/comments/vapb6z/eli5_what_is_docker/)
  - [youtube](https://www.reddit.com/r/docker/comments/vapb6z/eli5_what_is_docker/)

**Day 17 of day 57**
- *I am working on making Sign-Up pages with django and adding other fields according to user desire. For that today, I learned about Meta class with help us to add attribute to the class and also type of fields data.Currently I am facing challenge on migration part of model.I will leave link to repo of Sign-up after it's completion.*
- Resource
  - [geeksforgeeks about fields](https://www.geeksforgeeks.org/positiveintegerfield-django-models/)
  - [Meta class from official doc](https://docs.djangoproject.com/en/4.0/topics/forms/modelforms/#overriding-the-default-fields)
