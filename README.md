# libpypeg - A C library

The `libpypeg` C library provides <SUMMARY-OF-FUNCTIONALITY>.


## Usage

To start using `libpypeg` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: libpypeg ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = libpypeg%lib{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
lib{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libpypeg.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
