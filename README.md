
# DNABERT_2-Muon

This model is a fork of [DNABERT-2](https://github.com/MAGICS-LAB/DNABERT_2/tree/main) with the option of using [Muon](https://kellerjordan.github.io/posts/muon/) as hidden layer weights optimizer.

It is trained from scratch on [GUE/virus_covid](https://huggingface.co/datasets/leannmlindsey/GUE/viewer/virus_covid). Final weights can be downloaded [here](https://drive.google.com/file/d/17eqVcOxy8_l9j-fJV1CrBwcjA8kWjtSy/view?usp=drive_link).

## How to run training yourself
First, follow the official DNABERT-2 packages checklist. Then:

```
!pip install git+https://github.com/KellerJordan/Muon
!pip uninstall triton -y # triton errors out
```

Then, from one level above, run
```
python -m DNABERT.run_mlm DNABERT/args.json
```
