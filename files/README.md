# Nishanks JupyterLite 

JupyterLite deployed as a static site to GitHub Pages.

## ✨ Try it in your browser ✨

➡️ **https://nishanknavelkar.github.io/jupyter-lite/**

![github-pages](https://user-images.githubusercontent.com/591645/120649478-18258400-c47d-11eb-80e5-185e52ff2702.gif)


### Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- Configuring: https://jupyterlite.readthedocs.io/en/latest/configuring.html
- Deploying: https://jupyterlite.readthedocs.io/en/latest/deploying.html

### Deploy a new version of JupyterLite

To change the version of the prebuilt JupyterLite assets, update the `jupyterlite` package version in the [requirements.txt](./blob/main/requirements.txt) file.

The `requirements.txt` file can also be used to add extra prebuilt ("federated") JupyterLab extensions to the deployed JupyterLite website.

Commit and push any changes. The site will be deployed on the next push to the `main` branch.

## Development

Create a new environment:

```bash
mamba create -n jupyterlite-demo
conda activate jupyterlite-demo
pip install -r requirements.txt
```

Then follow the steps documented in the [Configuring](https://jupyterlite.readthedocs.io/en/latest/configuring.html) section.
