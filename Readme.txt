ReadMe File
============

This is web development application and data analysis project and deployment

The flask app is deployed on EC2 on AWS at: http://13.52.254.151/

The frontend in developed using flask web form connected to mongo db locally before deployment.

I install the mongo db on EC2 as well

The application uses python class 'USER' to extract all the data input fron the frontend to save it into csv format, which was load into jupyter notebook for the data analysis part.

All the charts generated is also save into '.png' format and copy to powerpoint for presentation.

File included
==========
Expenses directory - which contains all the python files and code
Data visualization - Jupyter notebook file for data analysis
User_detail_data_visualization - Powerpoint file for presentation

How to run the file
===============
Expenses directory that contain the python file
 
I use PyCharm IDE - 

Open PyCharm, navigate to Expenses folder open the folder into PyCharm, then in the terminal, run 'python app.py'.

Open cmd on window machine, run it as administrator, type mongod.exe - to run mongo db database. 

Open another cmd - run it as administrator , type mongosh (this is mongo db shell)

Go back to PyCharm, in terminal run python User.py to create the database inside mongo db

Also in terminal run python generate_db_data.py to populate the database with data

Run python User.py to generate the csv file for analysis.

Now Open anaconda, Jupyter notebook, navigate the to directory, open 'data visualization' and then click kernel, click restart and run all.

Also you can open the powerpoint file to see all the charts

Thank you. 

