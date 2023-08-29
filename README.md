# rg-bm25

Crude BM25 script abusing `rg`.

It implements [BM25](https://en.wikipedia.org/wiki/Okapi_BM25) for ranked text search.
No search indexing is done; searches are performed from scratch every time.

## Usage

You need to have installed Python 3,
[rg](https://github.com/BurntSushi/ripgrep#installation)
and [jq](https://github.com/jqlang/jq#installation)

Search in the current directory: `./rg-bm25 some keyword`

Best matches are shown at the bottom (unless the `--reverse` flag is given).

Run `./rg-bm25 --help` for more options.

## Demo

Example of `./rg-bm25 s3` running over the [rclone docs](https://github.com/rclone/rclone/tree/master/docs).
Best matches are at the bottom

![rg-bm25](https://user-images.githubusercontent.com/1336117/263998106-a36eef95-3f7c-46df-a6e8-0c2d08f27ebf.png)

