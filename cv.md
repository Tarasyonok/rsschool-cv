# Kirill Tarasov

###### Phone number: +7(909)655-20-08
###### Telegram: @tarasyonochek
###### e-mail: kir_tarasov@mail.ru

## About me

I'm 15 years old. Next academic year I will go to the ninth grade. I like programming. I am studying the programming language Python and WEB development. I play hockey.

## Languages and technologies I know

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original-wordmark.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/handlebars/handlebars-original-wordmark.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" width="50" hieght="50" />&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original-wordmark.svg" width="50" hieght="50" />&nbsp;

## Work experience

Familiarization with the scheme of work on Habr Freelance. The work has been completed: information content of the project using automation skills in Python. 

Python voice Assistant: code review, error correction assistance.

I have made projects: WEB application "quiz for programmers", chess in Python, websites and games in pygame.

## Python code example

Write a cached decorator that will cache the result of a function call.

```
def cached(func):
    results = {}
    
    def decorated_func(*args, **kwargs):
        nonlocal results
        
        if args in results:
            return results[args]
        else:
            result = func(*args, **kwargs)
            results[args] = result
            return result

    return decorated_func
```

An example of how my decorator can be used:

```
@cached 
def fib(n): 
    if n == 1 or n == 2: 
        return 1 
    else: 
        return fib(n - 1) + fib(n - 2)
```



## Education

(2023) Moscow School of Programmers
- Fullstack-developer: from your own website to a full-fledged web application.

(2023) Yandex Academy Lyceum
- Basics of programming in Python. Certificate № 2301 171664.

(2022) Online courses of the Sirius Educational Center
- Introduction to Python programming. Certificate with honors.

(2022) Foxford Online School
- Programming. Preparation for the Olympics, the initial level. grades 5-7.
- Programming. Preparation for the Olympiads, the average level of grades 7-9.
- I degree diploma for winning the Olympiad in English, grades 7-8.

(2022) Educational platform "Stepik"
- "Python Generation": a course for beginners. Certificate with honors.
- Programming in Python. Certificate with honors.

## English
level A2
