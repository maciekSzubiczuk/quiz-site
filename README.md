# quiz-site
A simple app for creating quizzes made using Flask framework. The app was made as a college project.

# Description:
This quiz creating module was developed by me as a part of a bigger college project. It allows user to create quizzes, solve them, edit them and delete them.

# Technologies:
- Python
- Flask
- SQLAlchemy
- HTML
- CSS
- JavaScript
- Bootstrap

# Setup:


## Prerequisites:

Clone repository using this command:
```
git clone https://github.com/maciekSzubiczuk/quiz-site.git
```

Install python3:

* Windows:
https://www.python.org/downloads/windows/
* Linux:
```
sudo apt install python3
```

* MacOS:
https://www.python.org/downloads/mac-osx/
or using homebrew:
```
brew install python3
```

Install pip:
https://pip.pypa.io/en/stable/installation/ 

Install pipenv:
https://pypi.org/project/pipenv/#installation


## Creating virtual environemnt: 

To create virutal environment and go into its terminal:
```
pipenv shell
```

Download required libraries:
```
pipenv install -r requirements.txt
```

Run the application:
```
flask run
```

After that app will be running at http://127.0.0.1:5000

# App instruction (App UI is in polish) :

To create a new quiz click on 'Stwórz swój własny Quiz!':

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/dfdfa071-0aea-42d3-a340-9ba5372270af)

Enter Title and Description:

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/10c8f387-6886-4b68-881c-8d697e42c708)


Press 'Dodaj Pytanie' to add question:

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/9d5d2f66-3c81-4209-b909-cea45149975a)

To add an answer we press the button 'Dodaj odpowiedź' and then type the content of the answer and check the box if the answer is to be correct:

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/c54a949d-9335-4341-9af2-ab7b96cbefb5)

After adding all the questions and answers press 'Dodaj Quiz', app will redirect to home page:

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/7ac3989f-46b6-4e91-ba91-41fcff32a270)

To solve a quizz press in the quizz icon, you will be redirected to solving page:

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/d9bea447-6ba8-483a-bb92-9696472280e7)

To edit quizz press three dots on the right side:

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/a855c8ed-f375-42b5-b242-ccca2a06beb8)

You will be redirected to edit page:

![image](https://github.com/maciekSzubiczuk/quiz-site/assets/106101693/adfbe443-32a1-4752-a26f-daa002051e8e)
