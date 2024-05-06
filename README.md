# Data Science Honors Thesis

_Sarah Song_

TO DO: set up binder link 

This project aims to develop and evaluate a custom tree canopy model for San Francisco using 2018 LiDAR data and NAIP aerial photography and applying three machine-learning algorithms: Random Forest (RF), XGBoost, and U-net. The U-net model demonstrated the highest accuracy among the tested models, matching the F1 Score for the "Tree" class across all models. This performance suggests that high-accuracy tree canopy prediction is feasible even with limited training data, offering a cost-effective alternative to outsourcing and supporting local urban forestry management efforts. Furthermore, this project explores demographic and environmental factors correlating with tree canopy coverage, emphasizing the relationships between tree canopy, PM2.5 levels, and demographic composition, thereby providing insights into environmental justice and urban planning.

## Directory Structure

This repo contains a few subfolders which contain the elements of this project.

| Folder | Description |
|-----|-----|
| `data`  | data from the original analysis in CSV, TSV, and pip-separated format  |
| `notebooks`  | Jupyter Notebook files  |

## Final Project Details

Your repo should contain _all_ of the folders listed above, and they should contain the appropriate files (e.g. the notebook with your analysis goes into the `notebooks` folder).

### MyBinder

You should note that this repository has a MyBinder link (at the top of this README), which links to MyBinder to allow others to run our code. _Your repository should also include such a link._ The steps to create this link are given below:

1. Copy the `requirements.txt` file from this repo and add it to yours. This should cover all dependencies, but if you use any that are not listed in that file, _make sure to add them_.
2. Go to the [MyBinder website](https://mybinder.org/) and paste the URL to your repo in the `GitHub repository name or URL` field (pictured below).
3. Include the brach name in the `Git branch, tag, or commit` field; for most, this will be `master`.
4. Open the dropdown below the Binder URL and copy the text next to the ![Markdown logo](images/markdown.png).
5. Paste this text into your README right below where your names are listed at the top. For our repo, it looked like this:

```markdown
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ls88-openscienceconnector/final-project/master)
```

Here is a screenshot of the website filled out for this repo:

![Binder Screenshot](images/binder.png)

### Github Best Practices

Note that this repository has a README and that each subfolder (except for the `images` folder) has a README as well. This should be reflected in the repo that you submit.

Make sure that your files render properly in Github. For example, Github does not render the LaTeX `\limits` command, and any display math that uses it will not be rendered.

**License:** Your repository should have a license on it. For most, if not all, of you, this will be a CC0 license, however we leave it at your discretion to choose the license for your project. Because Github no longer lists the CC0 template in its template chooser, we provide a link below to load this template into your repository. To use it, simply replace `<repo>` with the name of your repository.

> `https://github.com/ls88-openscienceconnector/<repo>/community/license/new?branch=master&template=cc0-1.0`

### Deliverables

Your project should have some deliverable (e.g. PDF, PPT, data). These should be uploaded in the `output` folder of your repo. If it is not a file you can upload (e.g. a Google Slides presentation), it should be linked-to in the README for that folder (even if this means you have a folder that is empty except for a README).

## Sources
