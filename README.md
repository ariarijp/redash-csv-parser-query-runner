# Redash CSV parser Query Runner

## Installation

```
$ pip install git+https://github.com/ariarijp/redash-csv-parser-query-runner
```

Then, add `redash_csv_parser_query_runner` to `REDASH_ADDITIONAL_QUERY_RUNNERS` in `.env` file or something like that.

```
export REDASH_ADDITIONAL_QUERY_RUNNERS="redash_csv_parser_query_runner"
```

Finally, restart Redash processes.

```
$ sudo service supervisor restart
```

## Usage

### Data Source options

* Delimiter (Required)
  * e.g. `,`

### Query format

Below is the example of query.

```
SepalLength,SepalWidth,PetalLength,PetalWidth,Name
5.1,3.5,1.4,0.2,Iris-setosa
4.9,3.0,1.4,0.2,Iris-setosa
4.7,3.2,1.3,0.2,Iris-setosa
4.6,3.1,1.5,0.2,Iris-setosa
5.0,3.6,1.4,0.2,Iris-setosa
5.4,3.9,1.7,0.4,Iris-setosa
4.6,3.4,1.4,0.3,Iris-setosa
5.0,3.4,1.5,0.2,Iris-setosa
4.4,2.9,1.4,0.2,Iris-setosa
4.9,3.1,1.5,0.1,Iris-setosa
5.4,3.7,1.5,0.2,Iris-setosa
4.8,3.4,1.6,0.2,Iris-setosa
4.8,3.0,1.4,0.1,Iris-setosa
4.3,3.0,1.1,0.1,Iris-setosa
```

## License

MIT

## Author

[ariarijp / Takuya Arita](https://github.com/ariarijp)
