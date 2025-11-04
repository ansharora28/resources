# Directory of Resources for FOSS maintainers

https://resources.opensourcelobby.org/ is a curated directory + compilation of valuable resources on the internet that can help maintainers to create, manage, and grow a FOSS project. This is a [opensourcelobby](https://opensourcelobby.org/) initiative.

## Contributing

All resources are listed in the [data.yml](data.yml) file. To add a new resource or change something, submit a PR with a patch to it. The website will be updated automatically upon merge.

Ensure adding suitable `category` (eg. Funding, Security, Documentation) and `type` (eg. fund, worksheet, knowledge-base) tags to your entries.


## Building locally
The website is a set of static HTML pages that are automatically generated from the Jinja template file `template.html`. The static assets are in the `static` directory.

1. Clone the repo.
2. `pip install -r requirements.txt`
<!-- 3. # `python build.py` to generate the static site into the `site` directory. -->

## License
The repository, data, and the static site generated are licensed under the Creative Commons Attribution-ShareAlike License.

## Attributions

The directory is made using [Dirmaker](). Credit to [Jeswin Jose]() for logo design.
