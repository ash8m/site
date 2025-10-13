# MyAccessID UK User Community Website

This repo contains the files used to create the website for the UK MyAccessID User Community.

This community is being set up via the NetworkPlus project [Exploring the Governance Requirements for Enabling UK DRIs to Adopt MyAccessID](https://nfcs-networkplus.ac.uk/projects/exploring-the-governance-requirements-for-enabling-uk-dris-to-adopt-myaccessid/).

## Contributing

If you would like to contribute to the site, please fork the repository and submit a pull request with your changes. We welcome contributions of all kinds, including documentation improvements, bug fixes, and new features.

## Building the Site Locally

To build the site locally, you will need to have [Conda](https://docs.conda.io/en/latest/) installed. You can then create a new environment using the provided `environment.yml` file:

```bash
conda env create -f environment.yml
conda activate myaccessid-uk-site-env
```

Once the environment is activated, you can build the site using [MkDocs](https://www.mkdocs.org/):

```bash
mkdocs serve
```

This will start a local development server at `http://127.0.0.1:8000`. You can then open this URL in your web browser to view the site.

To stop the server, press `Ctrl+C` in the terminal.

## Deploying the Site

The site is automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch. You can also manually deploy the site by running:

```bash
mkdocs gh-deploy
```

This will build the site and push the generated files to the `gh-pages` branch of the repository.

## License

This project is licensed under the [CC0-1.0 License](https://creativecommons.org/publicdomain/zero/1.0/). See the [LICENSE](LICENSE) file for details.
