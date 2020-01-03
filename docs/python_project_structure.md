# Python Project Structure

In following the guide from [Real Python - Python Application Layouts](https://realpython.com/python-application-layouts/), this repository will use the basic layouts for One-Off Scripts and Installable Single Packages.

## One-Off Scripts

```
helloworld/
│
├── .gitignore
├── helloworld.py
├── LICENSE
├── README.md
├── requirements.txt
├── setup.py
└── tests.py
```

## Installable Single Packages

```
helloworld/
│
├── helloworld/
│   ├── __init__.py
│   ├── helloworld.py
│   └── helpers.py
│
├── tests/
│   ├── helloworld_tests.py
│   └── helpers_tests.py
│
├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
└── setup.py
```

[The Hitchhiker's Guide to Python - Structuring Your Project](https://docs.python-guide.org/writing/structure/) is also a good guide on python project structure.