# Python testing
Set of tools that helps you improve your TDD skills, write your tests and python code into the `src` folder and thanks to nodemon you can see your output as soon as you save your changes.

## Requirements
- [Python 3.*](https://www.python.org/downloads/release/python-3111/)
- [Nodemon](https://www.npmjs.com/package/nodemon)

## Installation
Feel free to use any virtualenv tool such as pyenv, pipenv, poetry and so on.
```
pip install --upgrade pip
pip install -r requirements.txt
```

### Nodemon

```sh
sudo npm install -g nodemon
```

## Running
```sh
nodemon --ext py --exec "python -m pytest -vv src/**"
```

### Success
![Success](/img/screen1.png)

### Failure
![Failure](/img/screen2.png)