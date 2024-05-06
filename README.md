# Data Science Honors Thesis

_Sarah Song_

This project aims to develop and evaluate a custom tree canopy model for San Francisco using 2018 LiDAR data and NAIP aerial photography and applying three machine-learning algorithms: Random Forest (RF), XGBoost, and U-net. The U-net model demonstrated the highest accuracy among the tested models, matching the F1 Score for the "Tree" class across all models. This performance suggests that high-accuracy tree canopy prediction is feasible even with limited training data, offering a cost-effective alternative to outsourcing and supporting local urban forestry management efforts. Furthermore, this project explores demographic and environmental factors correlating with tree canopy coverage, emphasizing the relationships between tree canopy, PM2.5 levels, and demographic composition, thereby providing insights into environmental justice and urban planning.

## Directory Structure

This repo contains a few subfolders which contain the elements of this project.

| Folder | Description |
|-----|-----|
| `data`  | data from the original analysis in CSV, TSV, and pip-separated format  |
| `notebooks`  | Jupyter Notebook files  |


### Github Best Practices

Note that this repository has a README and that each subfolder (except for the `images` folder) has a README as well. This should be reflected in the repo that you submit.

Make sure that your files render properly in Github. For example, Github does not render the LaTeX `\limits` command, and any display math that uses it will not be rendered.

**License:** Your repository should have a license on it. For most, if not all, of you, this will be a CC0 license, however we leave it at your discretion to choose the license for your project. Because Github no longer lists the CC0 template in its template chooser, we provide a link below to load this template into your repository. To use it, simply replace `<repo>` with the name of your repository.

> `https://github.com/ls88-openscienceconnector/<repo>/community/license/new?branch=master&template=cc0-1.0`
