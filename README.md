# DataOps FiftyOne
This repository contains example demo how to use fiftyone as DataOps Preprocessing Tools.

## Sample Datasets

## Geting Started

### Run Dev Container
First, you need to install vscode devcontainer and run vscode devcontainer in this repository. For more info about devcontainer you can visit the [Official Documentation](https://code.visualstudio.com/docs/devcontainers/create-dev-container).

### Run JupyterLab Server
You can run the jupyterlab server inside devcontainer using command below.
```bash
bash run_jupyter_notebook.sh
```

The ouput should be like this:
```bash
root@docker-desktop:/workspaces/dataops-fiftyone# bash run_jupyter_notebook.sh 
[I 2023-10-24 15:33:39.857 ServerApp] Package jupyterlab took 0.0000s to import
[I 2023-10-24 15:33:39.862 ServerApp] Package jupyter_server_fileid took 0.0047s to import
[I 2023-10-24 15:33:39.880 ServerApp] Package jupyter_server_terminals took 0.0183s to import
[I 2023-10-24 15:33:40.027 ServerApp] Package jupyter_server_ydoc took 0.1458s to import
[I 2023-10-24 15:33:40.027 ServerApp] Package nbclassic took 0.0000s to import
[W 2023-10-24 15:33:40.030 ServerApp] A `_jupyter_server_extension_points` function was not found in nbclassic. Instead, a `_jupyter_server_extension_paths` function was found and will be used for now. This function name will be deprecated in future releases of Jupyter Server.
[I 2023-10-24 15:33:40.030 ServerApp] Package notebook_shim took 0.0000s to import
[W 2023-10-24 15:33:40.030 ServerApp] A `_jupyter_server_extension_points` function was not found in notebook_shim. Instead, a `_jupyter_server_extension_paths` function was found and will be used for now. This function name will be deprecated in future releases of Jupyter Server.
[I 2023-10-24 15:33:40.034 ServerApp] jupyter_server_fileid | extension was successfully linked.
[I 2023-10-24 15:33:40.037 ServerApp] jupyter_server_terminals | extension was successfully linked.
[I 2023-10-24 15:33:40.044 ServerApp] jupyter_server_ydoc | extension was successfully linked.
[W 2023-10-24 15:33:40.048 LabApp] 'token' has moved from LabApp to ServerApp. Be sure to update your config before our next release.
[W 2023-10-24 15:33:40.051 ServerApp] ServerApp.token config is deprecated in 2.0. Use IdentityProvider.token.
[I 2023-10-24 15:33:40.051 ServerApp] jupyterlab | extension was successfully linked.
[I 2023-10-24 15:33:40.054 ServerApp] nbclassic | extension was successfully linked.
```

you can visit your http://localhost:8008/lab/tree/ to access the jupyter lab.

### Run Jupyter Notebook
After the server is up, you can open http://localhost:8008/lab/tree/dataops-fiftyone.ipynb to access the notebook.

## Have Any Question?
You can reach me on my social media link:
- [linkedin](https://www.linkedin.com/in/haikalardikatama/)