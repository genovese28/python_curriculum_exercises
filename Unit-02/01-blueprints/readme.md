# Blueprints 

### Part I - Questions

1. Describe the MVC pattern.
a design pattern for building large web apps. model-managing data storage, retrieval and validation. view- user sees and we want it simple. Controller- the 'brains', talks to models and updates view.
2. In the MVC pattern, does the model communicate directly with the view? no the controller has to.
2. What is the purpose of blueprints? its for structure and organization of large crud apps. 
3. How does using blueprints help us organize bigger applications? through folders and files.

### Part II - Exercise

1. Refactor your users and messages app to use blueprints.  Make sure to have a separate file for `models.py`, `views.py`, and `forms.py`. You should have a working 1 to Many application with blueprints when this exercise is complete!

2. Include the following flash messages (it's important you make sure these are exact so the tests will pass)
    - when a user is created, send a flash message of "User Created!"
    - when a user is updated, send a flash message of "User Updated!"
    - when a user is deleted, send a flash message of "User Deleted!"
    - when a message is created, send a flash message of "Message Created!"
    - when a message is updated, send a flash message of "Message Updated!"
    - when a message is deleted, send a flash message of "Message Deleted!"

3. If you have not added any styling or testing to your users and messages app, be sure to do so!
