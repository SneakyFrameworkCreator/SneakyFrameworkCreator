- 👋 Hi, I’m @SneakyFrameworkCreator
- 👀 I’m interested in IT and computers
- 🌱 I’m currently learning Frameworks
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me my mail: autismguy843@gmail.com
- 😄 Pronouns: Class 5 IT guy
- ⚡ Fun fact: I have cheesecake obsession
# My brain in a nutshell
```python
import brain
day = 6
if(day == 6):
  brain.disabled()
  print("I love Saturdays")
  brain.relax()
else:
  print("The best day is friday")
```
# Publish Pypi package tutorial
```bash
my-module
-->mymodule
--->__init__.py
--->YOUR_SCRIPT_NAME.py
setup.py
```
## Example setup.py
```python
from setuptools import setup, find_packages

setup(
    name='CloakSDK',
    version='0.0.0.1',
    packages=find_packages(),
    author='frane',
    author_email='autismguy843@gmail.com',
    description='Simple framework to text',
    classifiers=[
        "Development Status :: 4 - Beta",
        "Natural Language :: Polish",
        "Programming Language :: Python :: 3.12",
    ]
)

```
## Export to whl file
```python
python setup.py sdist bdist_wheel
```
## upload to pypi 
- Use this
  ```bash
  twine upload dist/*
  ```
  ### or
  ```bash
  twine upload --username nazwa_użytkownika --password 'twoje_hasło' dist/*
  ```
