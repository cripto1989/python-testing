### Python Testing
Is a project which you can use to write fast unit tests, just write your code within src folder and run the nodemon command.

### Installation

Pipenv

```sh
pipenv install
```

Nodemon

```sh
sudo npm install -g nodemon
```

### Run
```sh
nodemon --ext py --exec "pipenv run pytest src/**"
```
