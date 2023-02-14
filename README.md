# Sample API testing

**Project setup**

```sh
git clone https://github.com/Nikita-Filonov/sample_api_testing.git
cd sample_api_testing

pip install virtualenv
virtualenv venv
source venv/bin/activate

pip install -r requirements.txt
```

**Starting auto tests**

```sh
python -m pytest --alluredir=./allure-results
```

```sh
allure serve
```

or

```sh
allure generate --clean
```
