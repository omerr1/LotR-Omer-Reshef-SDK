# Lord of the Rings SDK
## Helps you to rule the one

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

The SDK allows to have easier time when using the following API - https://the-one-api.dev/
### Must visit the website to obtain token to be able to access the API ###


## Installation

Requires python >=3.3 to run.

To install the package use:

```sh
pip install LotR-Omer-Reshef-SDK==0.3
```

In an IDE use 

```sh
from LotR_Omer_Reshef_SDK import LoTR_SDK
```

## Development

The following functions are available:

Setting a token. Must do it before using the other functions.

```sh
set_token(t)
```

Getting characters from LotR. Can specify name, race, gender, or none to receive all.

```sh
get_characters(name="Gandalf", race="", gender="")
```

Getting information about the books. 1-fellowship, 2-two towers, 3-return of the king.

```sh
get_books(num=0)
```

Getting quotes from the movies. Can specify 1-fellowship, 2-two towers, 3-return of the king for quotes from said movie.

```sh
get_quotes(movie_num = 0)
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

