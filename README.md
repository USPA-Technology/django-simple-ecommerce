<p align="center">
  <p align="center">
    <a href="https://justdjango.com/?utm_source=github&utm_medium=logo" target="_blank">
      <img src="https://assets.justdjango.com/static/branding/logo.svg" alt="JustDjango" height="72">
    </a>
  </p>
  <p align="center">
    The Definitive Django Learning Platform.
  </p>
</p>

# Django Simple E-commerce

This is a simple e-commerce website built with Django. It contains the essentials for adding products and capturing payments
online.

## Running this project

To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
pip install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
virtualenv env
```

That will create a new folder `env` in your project directory. Next activate it with this command on mac/linux:

```
source env/bin/active
```

Then install the project dependencies with

```
pip install -r requirements.txt
```

Now you can run the project with this command

```
python manage.py runserver
```

**Note** if you want payments to work you will need to enter your own Stripe API keys into the `.env` file in the settings files.

---

## Follow the tutorial

This project is part of a [series on YouTube](https://youtu.be/z4USlooVXG0) that teaches how to build an e-commerce website with Django.

---


This project is part of a course on [JustDjango](https://learn.justdjango.com)

---

<div align="center">

<i>Other places you can find us:</i><br>

<a href="https://www.youtube.com/channel/UCRM1gWNTDx0SHIqUJygD-kQ" target="_blank"><img src="https://img.shields.io/badge/YouTube-%23E4405F.svg?&style=flat-square&logo=youtube&logoColor=white" alt="YouTube"></a>
<a href="https://www.twitter.com/justdjangocode" target="_blank"><img src="https://img.shields.io/badge/Twitter-%231877F2.svg?&style=flat-square&logo=twitter&logoColor=white" alt="Twitter"></a>

</div>
