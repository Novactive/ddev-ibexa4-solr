## What is this?

This repository allows you to quickly install Apache Solr for Ibexa 4+ into a [Ddev](https://ddev.readthedocs.io) project using just `ddev get ddev/ddev-ibexa4-solr`.
It follows the [Ibexa 4.4 configuration](https://doc.ibexa.co/en/4.4/search/solr_search_engine) recipe.

## Installation on Ibexa 4.4

1. `ddev get ddev/ddev-ibexa4-solr && ddev restart`

1. `ddev restart`


## Configure your ibexa project

https://doc.ibexa.co/en/4.4/search/solr_search_engine/#step-1-configure-and-start-solr

## Alternate Core Name

If you want to use a core name other than the default "collection1", add a `.ddev/docker-compose.solr-env.yaml` with these contents, using the core name you want to use:

Special Mentions and Credits
----------------------------

- This ddev add-on is inspired by https://github.com/ddev/ddev-drupal9-solr