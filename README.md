# cedar-api-demo
Demonstrate use of the Cedar API developed by https://metadatacenter.org/

[CedarApiDemo.ipynb]

## API Key

The Cedar API requires an API, which you get by creating an account at https://cedar.metadatacenter.org/.
Once you have logged-in, navigate to your profile, and copy the value of the API keyand save it in a file
called ".cedarkey" in your home directory:

* Linux/MacOS - $HOME/.cedarkey
* Windows users - %USERPROFILE%/.cedarkey

__NOTE:__ You may also have to adjust the line that gets the cedarkeypath to use the USERPROFILE variable.

## Usage

To run just the code you see in the notebook on github, you'll need only Python 3 and the package `requests`.

To run the notebook on your computer, do this:

        pip install -r requirements.txt --user
        jupyter notebook

Bonus points if you can use a virtual environment:

        virtualenv venv
        . venv/bin/activate
        pip install -r requirements.txt
        jupyter notebook


## Other python packages that may be of use:

Including these packages will allow you to convert Cedar's templates into RDF/XML or TTL:

[lxml](https://pypi.org/project/lxml/)
[rdflib](https://pyyi.org/project/rdflib/)
[rdflib-jsonld](https://pypi.org/project/rdflib-jsonld/)


