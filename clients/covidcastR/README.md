# covidcastR

Provides R access to the [COVIDcast
API](https://cmu-delphi.github.io/delphi-epidata/api/covidcast.html) published
by the [Delphi group](https://delphi.cmu.edu/) at [Carnegie Mellon
University](https://www.cmu.edu). This API provides daily access to a range of
COVID-related signals Delphi collects from a variety of sources, including
cases, deaths, symptom surveys, healthcare data, and other information.

Consult the [COVIDcast API
documentation](https://cmu-delphi.github.io/delphi-epidata/api/covidcast.html)
for details on the data included in the API, licensing, and how to cite this
data in your work. **You should also consider subscribing to the [API mailing
list](https://lists.andrew.cmu.edu/mailman/listinfo/delphi-covidcast-api)** to
be notified of package updates, new data sources, corrections, and other
updates.

The [signals
documentation](https://cmu-delphi.github.io/delphi-epidata/api/covidcast_signals.html)
lists all the data sources and signals available through this API.

## Installing

This package is not on CRAN yet, so it can be installed using the
[`devtools`](https://cran.r-project.org/package=devtools) package:

```r
devtools::install_github("cmu-delphi/covidcast", ref = "main",
                         subdir = "clients/covidcastR")
```

## Documentation

The package documentation and examples are [available
online](https://cmu-delphi.github.io/covidcast/covidcastR/index.html).
