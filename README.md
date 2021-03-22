# EqualStreetNames-Groningen

This repo contains the submodule containing the data for Groningen in the EqualStreetNames project. For more information about the project, visit the [main repo](https://github.com/EqualStreetNames/equalstreetnames).

## Data updates

The data is updated every thursday by Github Actions:
[[![Update data](https://github.com/EqualStreetNames/equalstreetnames-groningen/actions/workflows/update-data.yml/badge.svg)](https://github.com/EqualStreetNames/equalstreetnames-groningen/actions/workflows/update-data.yml)

Afterwards the new version of the site is pushed to the `gh-pages` branch:
[![Deploy](https://github.com/EqualStreetNames/equalstreetnames-groningen/actions/workflows/deploy.yml/badge.svg)](https://github.com/EqualStreetNames/equalstreetnames-groningen/actions/workflows/deploy.yml)

## Contributing

If you notice any errors specifically in the submodule, feel free to open an issue, or submit a pull request.

If you want to add to the data itself, you can map it on [OpenStreetMap](https://osm.org/). You can use the tag `name:etymology:wikidata` for adding the information to a street using a [Wikidata](https://wikidata.org) entity.
