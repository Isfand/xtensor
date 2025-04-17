# xtensor - A C++ library

The `xtensor` C++ library provides <SUMMARY-OF-FUNCTIONALITY>.

## Repository
Add this location into your repositories.manifest under 'role: prerequisite'
location: https://github.com/Isfand/xtensor.git#master

## Usage

To start using `xtensor` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: xtensor ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = xtensor%lib{<TARGET>}
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
[bool] config.xtensor.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
