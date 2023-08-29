# rg-bm25

Crude BM25 script abusing `rg`.

It implements [BM25](https://en.wikipedia.org/wiki/Okapi_BM25) for ranked text search.
No search indexing is done; searches are performed from scratch every time.

## Usage

You need to have installed Python 3,
[rg](https://github.com/BurntSushi/ripgrep#installation)
and [jq](https://github.com/jqlang/jq#installation)

Search in the current directory: `./rg-bm25 some keyword`

Run `./rg-bm25 --help` for more options.
