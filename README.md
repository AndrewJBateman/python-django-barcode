# :zap: Python Django BarCode

* Python-Django app to create & display barcodes
* Code from a tutorial by [Pyplane](https://www.youtube.com/channel/UCQtHyVB4O4Nwy1ff5qQnyRw) - see [:clap: Inspiration](#clap-inspiration) below.

## :page_facing_up: Table of contents

* [:zap: Python Django BarCode](#zap-python-django-barcode)
	* [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
	* [:books: General info](#books-general-info)
	* [:camera: Screenshots](#camera-screenshots)
	* [:signal_strength: Technologies](#signal_strength-technologies)
	* [:floppy_disk: Setup](#floppy_disk-setup)
	* [:computer: Code Examples](#computer-code-examples)
	* [:cool: Features](#cool-features)
	* [:clipboard: Status & To-do list](#clipboard-status--to-do-list)
	* [:clap: Inspiration](#clap-inspiration)
	* [:envelope: Contact](#envelope-contact)

## :books: General info

* Django framework: used to tba

## :camera: Screenshots

![screen print](./img/admin.png)

## :signal_strength: Technologies

* [Python v3](https://www.python.org/) programming language
* [Django v3](https://www.djangoproject.com/) server-side web framework
* [python-barcode v0.13.1](https://pypi.org/project/python-barcode/) to create barcode. Supports barcode formats: EAN-8, EAN-13, EAN-14, UPC-A, JAN, ISBN-10, ISBN-13, ISSN, Code 39, Code 128, PZN
* [Pillow v8](https://pypi.org/project/Pillow/) Python Imaging Library (Fork)

## :floppy_disk: Setup

* [Install Python](https://docs.python-guide.org/starting/installation/)
* [Install pip](https://docs.python-guide.org/dev/virtualenvs/#installing-pipenv)
* [Install Django](https://docs.djangoproject.com/en/3.1/howto/windows/) by typing `pip install Django`
* Run `django-admin startproject barcode` to create a new project [ref. docs](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)
* Open `barcode` in VS Code
* Run `python manage.py startapp products` to create Python module
* Add code
* Run `pip freeze` to see list of modules installed. [Ref. Docs](https://pip.pypa.io/en/stable/reference/pip_freeze/)
* Run `python manage.py makemigrations`
* Run `python manage.py migrate`
* To add a superuser Run `python manage.py createsuperuser --username=joe --email=joe@example.com` [Ref. Docs](https://docs.djangoproject.com/en/3.1/topics/auth/default/)
* Run `python manage.py runserver` to run server on port 8000 and open /admin console

## :computer: Code Examples

* extract from tba

```python
)
```

## :cool: Features

* tba

## :clipboard: Status & To-do list

* Status: Working
* To-do: Comment code, complete readme

## :clap: Inspiration

* [Pyplane: Youtube: Django barcode generator | How to create barcodes in Django)](https://www.youtube.com/watch?v=VDIJ4GgKxR8&t=102s)
* [python-barcode documentation](https://python-barcode.readthedocs.io/en/stable/barcode.html#creating-barcodes-as-image)

## :envelope: Contact

* Repo created by [ABateman](https://www.andrewbateman.org) - you are welcome to [send me a message](https://andrewbateman.org/contact)
