# Onyx

## Overview

PHP application skeleton based on Silex 2. Promote framework agnostic conception.

## Getting started

### Requirements

* docker, executable by your user (see official documentation to set it up)
* php >= 5.5.9

### Installation

Download deps, configure, ...
```bash
 make install
```

Launching web server (choose your port with WEB_PORT parameter, 80 if omitted)
```bash
 cd docker
 make WEB_PORT=82 start
```

See home page at http://localhost:82