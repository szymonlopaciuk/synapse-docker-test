# Test Synapse on Docker

1. Generate config and certificates:

`docker-compose run --rm -e SERVERNAME=[name] synapse generate`

2. Run:

`docker-compose up synapse`
