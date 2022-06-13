# groupchat

This is a simple groupchat application exposing webservices to authenticated admin and users.
It is extended from https://github.com/flask-admin/flask-admin.git
To run this example:

1. Clone the repository::

     git clone https://github.com/tdsgit/groupchat.git  
     cd groupchat

2. Create and activate a virtual environment::

     virtualenv env  
     source env/bin/activate 

3. Install requirements::  

     pip3 install -r 'requirements.txt'  

4. Run the application::

     python3 app.py    
    
5. open localhost:5000/admin/login on browser and login as   
     Login : admin   
     Password : secret  

The first time you run this example, a sample sqlite database gets populated automatically. To suppress this behaviour,
comment the following lines in app.py:::

     if not os.path.exists(database_path):
         build_sample_db()

TODO:   

1.group add option to user   - done 
2.edit user   - done
3.testing    
4.group names in dropdowns

etc     
