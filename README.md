# pySiteCollector

Simple Python3 site information collector based on a UDEMY course

## How to use
* Clone / Download the repository
* Create virtual environment with Python3 `virtualenv -p python3 pySiteCollector'
* Activate the environment `source pySiteCollector/bin/activate`
* Install the required tld package `pip install tld`

Now you can edit the main.py and have a look how the functions are used:
* simply use the `gather_info()` method that takes 2 arguments - name of the output folder and a full url address

### Example
`gather)info('google', 'https://www.google.com')`
