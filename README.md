# Addition and Subtraction Practice



This project demonstrates basic addition and subtraction functions in Python and tests them using pytest.



## Python Version



Python 3.12.6



## Setup



Create a virtual environment:



```powershell

py -3 -m venv .venv

```



Activate the virtual environment:



```powershell

.\.venv\Scripts\Activate.ps1

```



Install the required dependencies:



```powershell

python -m pip install -r requirements.txt

```



## Run Tests



Run all tests with:



```powershell

python -m pytest -v

```



## Arrange-Act-Assert



The tests use the Arrange-Act-Assert pattern. Arrange sets up the inputs and expected result, Act calls the function being tested, and Assert checks that the actual result matches the expected result.



## Gitignore



The `.gitignore` file prevents generated files such as the virtual environment, Python bytecode, and pytest cache files from being tracked by Git.


