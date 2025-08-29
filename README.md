[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cms-dpoa/cms-nikhef-tutorial/HEAD)

# CMS Open Data Tutorial

## First COMETA workshop on artificial intelligence for multi-boson physics, NIKHEF 2-3 Oct 2024

https://indico.cern.ch/event/1440583/overview

### Run in the terminal
```
$ virtualenv cms
$ source cms/bin/activate
$ pip install -r requirements.txt
$ jupyter lab
```

You may find (as I found on my Mac) that in the venv that despite installing `jupyter` in the venv that
the version used is still the system one. In this case you may find that running
```
$ cms/bin/jupyter lab
```
works.

### Run in Binder
Click on the "launch binder" above

## Acknowledgements
The ML example notebook has been adapted from [QCDJetMachineLearning](https://github.com/cernopendata-datascience/QCDJetsMachineLearning)

## Notes
Since the workshop the ML example notebook has been updated to use PyTorch instead of TensorFlow. The version of the notebook used in the workshop can be found by using the `nikhef` tag of this repo.