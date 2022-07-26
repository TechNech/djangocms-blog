
# djangocms-blog

## Issue 1: 
   Blog content is not shown on the post page. (# Fixed)

## Issue 2: 
   Media content is not shown on the post page. (# Fixed)

# Project Structure:
  ![project-structure](https://i.imgur.com/ChRHCti.png)

## Add a virtualenv to your project `ROOT` directory
  ### Install virtualenv using pip:
        pip install virtualenv
  ### Initialise the virtualenv      
        virtualenv venv
  ### Activate the virtualenv
      source venv/bin/activate
  
  ### CD to blog directory having manage.py
      cd blog

  ### Make migrations
      python manage.py migrate
  ### Run server
      python manage.py runserver
