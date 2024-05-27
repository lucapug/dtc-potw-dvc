# dtc-potw-dvc

DTC project of the week - DVC - may 2024

reference (extended tutorial): [AntonisCSt/POW_DVC: Data Version Control Tutorial/Repo for project-of-the-week DataTalksClub event (github.com)](https://github.com/AntonisCSt/POW_DVC/tree/main)

iterative.ai

#### DVC ecosystem of tools

DVC's products are modular, so you can pick-and-choose which to use or continue using your existing tools.

`dvc.org` (open source tools)

`dvc` data version control
`dvclive` (logger to track experiment runs (metrics, parameters) and models)
`cml` continuous machine learning (CI/CD)
`mlem` (package and simplify model deployment)
`dvc extension for vscode` (more powerful if dvclive is installed)

`dvc.ai`

`dvc studio` (collaboration platform for teams; https://studio.iterative.ai/
include model registry) [free version with restrictions]
`dvcx` data version control and data curation (metadata generation) for the genAI era

##### data versioning and making the choice of the version

commands involved:

(version stored in cache)
`dvc add`

(keep track on github)
`git add/commit/push`

(modify data file, add new version to dvc)
`dvc add`

(keep track on github)
`git add/commit/push`

(find commit of old version)
`git log` then
`git checkout commitID`

(align dvc with git)
`dvc checkout`

<br>
<br>
