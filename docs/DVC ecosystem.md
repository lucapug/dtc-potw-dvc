## DVC ecosystem of tools

DVC's products are modular, so you can pick-and-choose which to use or continue using your existing tools.

open source tools, each one has its own Github repo:

* `dvc` data version control
* `dvclive` (logger to track experiment runs (metrics, parameters) and models)
* `cml` continuous machine learning (used in combination with a CI/CD mechanism (as an example with GitHub Actions), can enrich the automation with ML oriented tasks (example: auto reports with plots associated to each PR))
* `mlem` (package and simplify model deployment)
* `gto` (git tag ops. Turn your Git repository into an Artifact Registry)
    Together with DVC, GTO serves as a backbone for Git-based Iterative Studio Model Registry.
* `dvc extension for vscode` (on MS marketplace; more powerful if dvclive is installed)

enterprise solutions:

* `dvc studio` (collaboration platform for teams; https://studio.iterative.ai/
    include model registry) [exists free version with restrictions]
* `dvcx` data version control and data curation (metadata generation) for the genAI era