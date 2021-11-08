# Changelog


## v1.0.2 (2021-11-08)

### Features

* Added basic input type validation to encode and decode (#49) [Ivan Savov]

### Fixes

* Use sys.version_info since sys.version returns string that interprets 3.10 as 3.1 in comparison. (#54) [Karthikeyan Singaravelan]


## v1.0.1 (2020-03-06)

### Fixes

* Use README as the long description on PyPI. [Stavros Korokithakis]


## v1.0.0 (2020-03-06)

### Features

* Drop support for Python before 3.5. [Stavros Korokithakis]

* Add simple command-line interface (#43) [Éric Araujo]

### Fixes

* Make encode and decode MSB-first (#36) [Keane Nguyen]

* Make the URL check more robust (fixes #32) [Stavros Korokithakis]


## v0.5.0 (2017-02-19)

### Features

* Make int_to_string and string_to_int available globally. [Stavros Korokithakis]


