# Directory of Resources for FOSS maintainers

https://resources.opensourcelobby.org/ is a curated directory + compilation of valuable resources on the internet that can help maintainers create, manage, and grow FOSS projects. This is an [opensourcelobby](https://opensourcelobby.org/) project.

## Contributing

All resources are listed in the [data.yml](data.yml) file. To add a new resource or change something, submit a PR with a patch to it. The website will be updated automatically upon merge.

Ensure adding suitable `category` (eg. Funding, Security, Documentation) and `type` (eg. fund, worksheet, knowledge-base) tags to your entries.

## Building locally

The website is a set of static HTML pages that are automatically generated from the Jinja template file `template.html`. The static assets are in the `static` directory.

1. Clone the repo.
2. `pip install -r requirements.txt`
3. `dirmaker --build`
4. `cd site`
5. `python3 -m http.server 8000` (to test locally)

## License

The repository, data, and the static site generated are licensed under the Creative Commons Attribution-ShareAlike License.

## Attributions

This directory is made using [Dirmaker](https://github.com/knadh/dirmaker). Credit to [Jeswin Jose](https://www.linkedin.com/in/jeswinjosu/) for logo design.
