django-report-builder
=====================

A GUI for Django ORM. Build custom queries and display results.
Targets sys admins and capable end users who might not be able to program or gain direct interactive shell access.

[![Build Status](https://travis-ci.org/burke-software/django-report-builder.png?branch=master)](https://travis-ci.org/burke-software/django-report-builder) [![Bountysource](https://www.bountysource.com/badge/tracker?tracker_id=314767)](https://www.bountysource.com/trackers/314767-burke-software-django-report-builder?utm_source=314767&utm_medium=shield&utm_campaign=TRACKER_BADGE)
[![Coverage Status](https://coveralls.io/repos/burke-software/django-report-builder/badge.svg)](https://coveralls.io/r/burke-software/django-report-builder)


# News

3.2 is released. 
This features a refactored report_to_list function which is responsible for generating the actual python list of data from the report object. 
Tests suggest a 10x speed improvement but your mileage may vary.

# What is Django Report Builder?

![](docs/screenshots/reportbuilderscreen.png)

## Features

- Add filters
- Add display fields
- Preview and create xlsx reports
- Very simple security, user must have change or "view" permission to view
reports. Unprivileged users can still build reports and see database schema.
- Model properties (thanks yekibud)
- Support for [django-custom-fields](https://github.com/burke-software/django-custom-field)
- Support for django-hstore
- Export to Report global admin action
- Optional asynchronous report generation

# Documentation

http://django-report-builder.readthedocs.org/

[Google group](https://groups.google.com/forum/#!forum/django-report-builder/).

# [Hacking](http://django-report-builder.readthedocs.org/en/latest/hacking/)

# Discussion

Let us know your thoughts at https://google.com/+Burkesoftware

[2.x]: https://github.com/burke-software/django-report-builder/tree/2.x
