# easyshop
Installation Setup : steps

git pull https:// this repository as it is public.
create python3 virtual environment. (python >= 3.6.5) : ~ python3 -m venv env_name
activate env : ~ source env_name/bin/activate
install requirements : ~ pip install -r path_to_req.txt
migrations : ~ python manage.py migrate
create superuser : ~ python manage.py createsuperuser
collect static files : ~ python manage.py collectstatic articulate_static
all these setup has dependency on settings.py, contact for settings.
Image upload default set to AWS s3 bucket i.e defined in settings.py
finally run server : ~ python manage.py runserver
