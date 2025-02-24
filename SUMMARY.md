# Table of contents

* [Grid in 3 minutes](README.md)

## Start Here

* [Typical workflow \(Web user\)](start-here/typical-workflow-web-user.md)
* [Typical workflow \(CLI user\)](start-here/typical-workflow-cli-user.md)

## Products

* [⚡CLI](products/global-cli-configs/README.md)
  * [Advanced config](products/global-cli-configs/advanced-config.md)
  * [API reference](products/global-cli-configs/cli-api/README.md)
    * [grid artifacts](products/global-cli-configs/cli-api/grid-artifacts.md)
    * [grid credentials](products/global-cli-configs/cli-api/grid-credentials.md)
    * [grid datastore](products/global-cli-configs/cli-api/grid-datastores.md)
    * [grid docs](products/global-cli-configs/cli-api/grid-docs.md)
    * [grid delete](products/global-cli-configs/cli-api/grid-delete.md)
    * [grid history](products/global-cli-configs/cli-api/grid-history.md)
    * [grid session](products/global-cli-configs/cli-api/grid-interactive.md)
    * [grid logs](products/global-cli-configs/cli-api/grid-logs.md)
    * [grid login](products/global-cli-configs/cli-api/grid-login.md)
    * [grid run](products/global-cli-configs/cli-api/grid-train.md)
    * [grid status](products/global-cli-configs/cli-api/grid-status.md)
    * [grid stop](products/global-cli-configs/cli-api/grid-cancel.md)
    * [grid user](products/global-cli-configs/cli-api/grid-user.md)
    * [grid version](products/global-cli-configs/cli-api/grid-version.md)
    * [grid view](products/global-cli-configs/cli-api/grid-view.md)
    * [grid ssh-keys](products/global-cli-configs/cli-api/grid-ssh-keys.md)
    * [grid sync-env](products/global-cli-configs/cli-api/grid-sync-env.md)
  * [Virtual Environments](products/global-cli-configs/virtual-environments.md)
  * [Windows support](products/global-cli-configs/using-grid-with-windows-subsystem-for-linux-wsl.md)
* [⚡Datastores](products/add-data-to-grid-datastores/README.md)
  * [Create](products/add-data-to-grid-datastores/create.md)
  * [Create from a Session](products/add-data-to-grid-datastores/create-from-a-session.md)
  * [Create from a cluster](products/add-data-to-grid-datastores/create-from-a-cluster.md)
  * [Periodic upload](products/add-data-to-grid-datastores/periodic-upload.md)
  * [FAQ](products/add-data-to-grid-datastores/datastore-faq.md)
* [⚡️Mobile](products/mobile/README.md)
  * [Metrics](products/mobile/metrics.md)
  * [Stop experiments](products/mobile/stop-experiments.md)
* [⚡Sessions](products/sessions/README.md)
  * [Attaching Datastores](products/sessions/attaching-datastores.md)
  * [Automatic Pausing](products/sessions/automatic-pausing.md)
  * [Github login](products/sessions/github-login.md)
  * [JupyterLab with Sessions](products/sessions/jupyterlab-with-sessions.md)
  * [Machines](products/sessions/machines.md)
  * [Pause](products/sessions/pause.md)
  * [SSH into a Session](products/sessions/how-to-ssh-into-a-session.md)
  * [Julia and R languages in Sessions](products/sessions/using-julia-and-r-languages-in-sessions.md)
  * [VSCode with Sessions](products/sessions/vscode-with-sessions.md)
* [⚡Runs](products/run-run-and-sweep-github-files/README.md)
  * [Actions](products/run-run-and-sweep-github-files/actions.md)
  * [Artifacts](products/run-run-and-sweep-github-files/artifacts.md)
  * [Attaching Datastores](products/run-run-and-sweep-github-files/attaching-datastores.md)
  * [Clone Runs or Experiments](products/run-run-and-sweep-github-files/cloning-runs-or-experiments.md)
  * [Failed jobs](products/run-run-and-sweep-github-files/failed-jobs.md)
  * [Hyperparameter sweeps](products/run-run-and-sweep-github-files/sweep-syntax.md)
  * [Lowering costs \(BETA\)](products/run-run-and-sweep-github-files/interruptible-machines.md)
  * [Machines](products/run-run-and-sweep-github-files/machines.md)
  * [Metrics \(charts\)](products/run-run-and-sweep-github-files/metrics-charts.md)
  * [Private Repos](products/run-run-and-sweep-github-files/private-repos.md)
  * [Sharing Runs](products/run-run-and-sweep-github-files/sharing-runs.md)
  * [Script dependencies](products/run-run-and-sweep-github-files/script-dependencies.md)
  * [Viewing logs](products/run-run-and-sweep-github-files/viewing-logs.md)
  * [YAML configs](products/run-run-and-sweep-github-files/yaml-configs/README.md)
    * [Using YAML](products/run-run-and-sweep-github-files/yaml-configs/yaml-api.md)
  * [FAQ](products/run-run-and-sweep-github-files/faq.md)
  * [Running PyTorch Lightning](products/run-run-and-sweep-github-files/running-pytorch-lightning.md)
  * [Running Tensorflow or Keras](products/run-run-and-sweep-github-files/running-tensorflow-or-keras.md)
  * [Running Julia programs](products/run-run-and-sweep-github-files/running-julia-programs.md)

## Examples

* [Vision](examples/vision/README.md)
  * [Coco Object Detection](examples/vision/coco.md)
  * [ImageNet classification](examples/vision/image-classification-with-imagenet.md)
  * [Kinetics Video Classification](examples/vision/kinetics-video-classification.md)
  * [MosMedData 3D Image Classification](examples/vision/mosmeddata-3d-image-classification.md)
  * [GANs using PyTorch Lightning](examples/vision/gans-using-pytorch-lightning.md)
* [NLP](examples/nlp/README.md)
  * [GPT 10B+ params \(8 GPUs\)](examples/nlp/gpt-10b+-params-8-gpus.md)
  * [XSum Text Summarization](examples/nlp/xsum-text-summarization.md)
  * [Text Classification](examples/nlp/text-classification.md)
* [Time Series](examples/time-series/README.md)
  * [Coin Market Cap Price Forecasting](examples/time-series/price-forecasting.md)
* [Self-supervised learning](examples/self-supervised-learning-1/README.md)
  * [SIMCLR](examples/self-supervised-learning-1/self-supervised-learning.md)

## Platform

* [Billing rates](platform/billing-rates.md)
* [Upgrades](platform/upgrades/README.md)
  * [Add custom cloud credential](platform/upgrades/adding-custom-cloud-credentials.md)
* [Early Access Features](platform/about-these-features/README.md)
  * [Multi-node training](platform/about-these-features/multi-node.md)
  * [Teams features](platform/about-these-features/teams-features.md)
* [Report issues](platform/report-issues/README.md)
  * [Feature Requests](platform/report-issues/feature-requests.md)
* [Supporting Workflows](platform/supporting-workflows-1/README.md)
  * [Keeping track of costs](platform/supporting-workflows-1/monitoring-costs.md)
  * [Payments and credits](platform/supporting-workflows-1/billing-and-credits.md)
  * [Viewing login credentials](platform/supporting-workflows-1/your-login-credentials.md)
* [Tips & Tricks](platform/tips-and-tricks.md)
* [Changelog](platform/changelog.md)
* [Security & Privacy](platform/security-and-privacy.md)
* [Status](platform/status.md)

## LINKS

* [Grid.ai Website](https://grid.ai)
* [Platform](https://platform.grid.ai)

