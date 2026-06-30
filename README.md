# ACCESS-OM3 Experiments

This repository is central location to store the automatically generated payu run-logs from ACCESS-OM3 experiments. Please all experiments which are being shared.

To get write access, you need to create an issue and request access, please use [this issue template](https://github.com/ACCESS-Community-Hub/access-om3-experiments/issues/new?template=add-user-request-to--access-om3-experiments--repository-.md).

### Branch name conventions
Branches in this repository use the experiment name, as defined the `name:` field in `metadata.yaml` for the experiment 

This typically requires using a different branch name on the git `remote`:

e.g. 
the MC (MOM-CICE) experiment branch labelled _25km_jra_ryf+wombatlite-test3_, was pushed to a remote branch labelled _MC-25km_jra_ryf+wombatlite-test3-f4d79e82_

``` bash
git remote add experiments https://github.com/ACCESS-Community-Hub/access-om3-experiments
git push -u experiments 25km_jra_ryf+wombatlite-test3:MC-25km_jra_ryf+wombatlite-test3-f4d79e82
```
