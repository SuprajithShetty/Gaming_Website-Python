About Project:

This is Gaming Webite, where you can log in and buy the games available.

Process to run:

After cloning install all the softwares which are mentioned in requirements.txt
Command for that is pip3 install -R requirements.txt

To run the code go to the file location and 

Whiule running this project you may face some eroors link 
( Desktop/gaming_project/GameStore$ python3 manage.py runserver
/home/suprajith/.local/lib/python3.10/site-packages/django/utils/translation/trans_real.py:76: DeprecationWarning: set_output_charset() is deprecated
  self.set_output_charset('utf-8')

ModuleNotFoundError: No module named 'django.apps' )


# Create a virtual environment called "myenv"
virtualenv myenv

# Activate the virtual environment
source myenv/bin/activate

# Install the required packages
pip install -r requirements.txt

# Run the project
python manage.py runserver

# Deactivate the virtual environment
deactivate
