## quay.io/esdc/julia-nb Dockerfile


This repository contains **Dockerfile** of a single user Jupyter Lab that is pre-configured with ESDL Python and Julia APIs.


### Base Docker Image

* [quay.io/esdc/singleuser-python-nb:0.5.2](https://quay.io/repository/esdc/singleuser-python-nb?tab=tags/)

### What's available on the Jupyter Lab?

* Python3 bundled in Conda installation (more detailed on the included packages can be found in the Dockerfile)

* esdl-core (latest)

* gridtools (latest)

* Julia 0.6.2


### Installation

1. Install [Docker](https://www.docker.com/).

2. `docker build -t quay.io/esdc/singleuser-julia-nb .` or `docker pull quay.io/esdc/singleuser-julia-nb`
