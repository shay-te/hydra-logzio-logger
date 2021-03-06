
[![PyPI](https://img.shields.io/pypi/v/hydra-logzio-logger)](https://pypi.org/project/hydra-logzio-logger/)
![PyPI - License](https://img.shields.io/pypi/l/hydra-logzio-logger)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/hydra-logzio-logger)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/hydra-logzio-logger.svg)](https://pypistats.org/packages/hydra-logzio-logger)


# Hydra Logzio Logger
Hydra Logzio Logger is a plugin [hydra](https://hydra.cc/)  plugin for logging data into logzio 


## License
Hydra Logzio Logger in licenced under [MIT](https://github.com/shay-te/hydra-logzio-logger/blob/master/LICENSE)

## Prerequisite
Before using set to following environment variables

`logzio_format`, `logzio_token`, `logzio_drain_timeout`, `logzio_url`

For more info about these variables read [here](https://app-eu.logz.io/#/dashboard/data-sources/Python).

## Example 

Create an new hydra config file 

```yaml
defaults:
  - hydra/job_logging: logzio_logger
  - hydra/hydra_logging: logzio_logger

my_app:
    some_conf: yada yada
...
```

See how to load the config file [here](https://hydra.cc/docs/intro) 

Thank you
 