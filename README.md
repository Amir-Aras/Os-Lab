# Os-Lab Assignment 5

### 1
- **Config git for push**
    - Open Terminal
    ```shell
    $ git config credential.helper store
    $ git push https://github.com/repo.git
    Username: <type your username>
    Password: <type your password>
    ```
    - Done

### 2
- **.gitignore**
     ```shell
     یک فایل است که گیت از ان استفاده میکنه برای این که مشخص کند کدام فایل و پوشه نباید در یک کد منبع داده شده نادیده گرفته شود
     ```
     - [Link to gitignore](https://github.com/github/gitignore)

- **.git**
     ```shell
     پوشه گیت شامل تمام اطلاعات لازم برای پروژه شما در کنترل نسخه و کلیه اطلاعات مربوط به کامیت ها,آدرس مخزن از راه دور و غیره است. همه آنها در این پوشه وجود دارد
     این همچنین شامل یک سیاهه مربوط به ذخیره تاریخچه تعهدات شما است تا بتوانید دوباره به تاریخ برگردید
     ```
- **git pull**
     ```shell
     دستور گیت پول میره اطلاعات رو از روی ریموت میگیره و اون اطلاعات رو نسخه ریموت ریپو ذخیره میکنه بعد از اون میاد اطلاعات نسخه ریموت رو با لوکال مرج میکنه
     ```
- **branch**
     ```shell
     برانچ یکی از ویژگی های موجود در اکثر سیستم های کنترل مدرن اند. که هر کد شامل یه برنچ مستر است و میتوان برانچ های دیگه برای پروژه تعریف کرد که افراد دیگه هستن و رویه پروژه کار میکنند
     ```

### 3
- **Add into github**
     ```shell
     $ mkdir tmp
     $ cd tmp/
     $ git init
     $ git checkout -b develop
     $ touch README.md
     $ git remote add origin {Link github ripo you created empty}
     $ git add .
     $ git commit -m "First commit"
     $ git checkout develop
     $ git merge --no-ff my-feature-branch
     $ git push origin develop
     ```
