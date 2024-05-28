# dtc-potw-dvc

DTC project of the week - DVC - may 2024

reference tutorial [here](https://github.com/AntonisCSt/POW_DVC/tree/main)

#### DVC ecosystem of tools (see in [docs](https://github.com/lucapug/dtc-potw-dvc/blob/main/docs/DVC%20ecosystem.md))

### making the choice of the data version

commands involved:

(version stored in cache)
`dvc add`

(keep track on github)
`git add/commit/push`

(modify data file, then add new version to dvc)
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
