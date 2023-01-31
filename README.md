# python-virtual-environments
how to use different python environments

## 1- venv
> `venv` is a bilt-in package in python3 and you don't need to install it.
###### how to create a virtual environment using `venv` :
```
python -m venv <my_venv_name>
```

--- 

## 2- virtualenv
###### to use `virtualenv` you need to install it :  
```
pip install virtualenv

```
###### how to to create a virutal-environment using `virtualenv` :
```
virtualenv <my_env_name>
```


---

## 3- pipenv
###### to use `pipenv` you need to install it :
```
pip install --user pipenv
```

###### how to to create a virutal-environment using `pipenv` :
> `pipenv` is a litle bit different from other env-tools . using code below , you can create and connect to your env.
```
pipenv shell
```

##### how to install a package using `pipenv`:
```
pipenv install <package>
```
