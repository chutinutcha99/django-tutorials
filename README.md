# django-tutorials
## This is Django Tutorials for Beginner to Advanced

## ขั้นตอนที่ 1 ใช้คำสั่งนี้
git clone https://github.com/chutinutcha99/django-tutorials.git ลงใน Teminal หรือ Command line

## ขั้นตอนที่ 2 ให้พิมพ์คำว่า
cd django-tutorials ใน command line หรือ terminal จากนั้น พิมพ์ว่า code . เพื่อเข้าสู่ vscode 

## ขั้นตอนที่ 3 สำหรับ Django Framework จะทำงานร่วมกับ virtual environment ทำการติดตั้งโดยใช้คำสั่งนี้

Windows:
py -m venv venv

Unix/MacOS: 
python -m venv venv

### ขั้นตอนที่ 4 ให้ทำการ activate ของ venv

Windows:
venv\Scripts\activate

Unix/MacOS: 
source venv/bin/activate

### ขั้นตอนที่ 5 ให้ทำการ Install โดยรันคำสั่งนี้

python -m pip install -r requirements.txt

### ขั้นตอนที่ 6 ให้ Runserver โดยใช้คำสั่งนี้

python manage.py runserver

### ขั้นตอนที่ 7 ให้ Makemigrations โดยใช้คำสั่งนี้

python manage.py makemigrations

### ขั้นตอนที่ 8 ให้ Migrate โดยใช้คำสั่งนี้

python manage.py migrate

หลังจากนั้นให้ทำงาน Runserver อีกครั้ง


 
