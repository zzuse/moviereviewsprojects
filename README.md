# Install Django on a python 3.8+ env
```
pip3 install Django
```

# create moviereviewsprojects
```
python3 -m django startproject moviereviews
mv moviereviews moviereviewsproject
```
# create movie sub apps
```
cd moviereviewsproject
python3 manage.py startapp movie
```
# run projects
```
python3 manage.py runserver
```