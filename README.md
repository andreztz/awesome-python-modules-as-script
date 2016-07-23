# Awesome Python modules as script

Catalogue of useful python modules that run as script.

## Requirements:
* Python 3

## How to use?

You have to type: `python -m <name>`.

You can access help through: `python -m <name> --help` ou `python -m <name> -h`.

Standard Library
----------------

| Name          | Description                                       | Example                                      |
| :------------ |:------------------------------------------------- |:---------------------------------------------|
| venv          | Create a virtual enviroment                       | python -m venv myproject                     |
| serve         | Simple HTTP Server                                | python -m http.server 5000                   |
| pydoc         | Consult the documentation                         | python -m pydoc -b                           |
| timeit        | Measuring execution time of small code snippets   | python -m timeit 'sorted(range(100))'        |
| profile       | Profiling your code                               | python -m profile some_module.py             |
| json.tool     | Validate and pretty-print JSON                    | echo '{ 1.2:3.4}' \| python -m json.tool     |
| calendar      | Pretty print a calendar                           | python -m calendar                           |
| site          | List your current path                            | python -m site                               |
| dis           | Print bytecode generated by a file                | python -m dis some_module.py                 |
| webbrowser    | Open a web browser                                | python -m webbrowser http://httpbin.org      |
| inspect       | Inspect a object.                                 | python -m inspect "collections:OrderedDict"  |
| tokenize      | Show how python tokenize a file                   | python -m tokenize some_module.py            |
| pip           | Python package manager                            | python -m pip install --user requests        |
| zipfile       | Zip operations like create, test or extract       | python -m zipfile -e zipfile.zip target      |
| code          | Closely emulate the interactive Python interpreter| python -m code                               |
| base64        | Encode and decode base64                          | echo 'message' \| python -m base64 -e        |
| doctest       | Run doctests in a file                            | python -m doctest myfile.py                  |

Third party packages
--------------------

| Name          | Description                                    |Example                    |
|:------------- |:---------------------------------------------- |:--------------------------|
| pytest        |Run tests using pytest                          | python -m pytest -s tests/|

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
