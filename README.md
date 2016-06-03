# company-cli
create a company from the command line interface


```
company init # if not already in a company repository, asks for:
# * type (choose from abstract-company implementations, e.g. company-uk-ltd)
# * name (check availability)
# * leads through the implementation independent setup process and generates the companies file structure
#   * @TODO: use "puke" idea
# * breaks if process needs manual steps to be completed in between and offers:
company continue # instead of `company init` in a repo that has a company with incomplete setup process

# the `company init` or `company continue` are greyed out and `company run` becomes available
company run # starts a dev server with a user interface to interact with the company (might also offer other "run cli usage)
```

**Related Projects:**
* [`company`](https://github.com/digitalsolopreneur/company) (a library that lets you create a company programatically)
* [`company-cli`](https://github.com/digitalsolopreneur/company-cli)(use "company" from the command line)
* [`abstract-company`](https://github.com/digitalsolopreneur/abstract-company)(specifies a standard interface to implement opening and running a company)
* [`company-uk-ltd`](https://github.com/digitalsolopreneur/company-uk-ltd)(as a first example implementation that fullfillfs "abstract-company")

Please check the roadmap too :-)
https://github.com/digitalsolopreneur/roadmap/issues
