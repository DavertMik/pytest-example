# Testomat.io Python Project

To run tests with XML report generarted:

```
pytest --junit-xml report.xml
```

To upload report to Testomat.io.

Install Testomat.io reporter

```
npx @testomatio/reporter --save
```

Run `npx report-xml` from `@testomatio/reporter` package.

```
TESTOMATIO={apiKey} npx report-xml --pytest report.xml
```


# pytest-example
pytest - Python Testing Example

This is a simple example of how to use pytest to integreate testing in your Python application.


## Usage
This example comes with several test files (e.g. test_app.py, test_funcs.py, etc.).


![Pytest Output](https://github.com/ptracesecurity/pytest-example/blob/media/pytest_output.png)



## Code Structure

```
myapp/
    app.py
    mymodule/
        __init__.py
        funcs.py
tests/
    __init__.py
    test_app.py
        mymodule/
            __init__.py
            test_additions.py
            test_funcs.py
```

## Contact

Author: Gianni Gnesa (gnix) (@GianniGnesa)[https://twitter.com/giannignesa]

For any question about this code, feel free to ask in the (PSEC Facebook Group))[https://www.facebook.com/groups/psec.community].
