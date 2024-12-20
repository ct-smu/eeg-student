# EEG package

## Stimuli Experiment, Signal Pre-process, Signal Analysis for ERP, ERDS, SSVEP

### Images for stimulus
If you want to get all images and videos for stimulus,
please contact to <lhw4846@smu.ac.kr>

### 🚀Quick setup

```bash
# clone project
git clone https://github.com/ct-smu/eeg-student.git
cd eeg

# [OPTIONAL] create conda environment
conda create -n myenv python=3.7
conda activate myenv

# install requirements
pip install -r requirements.txt
```

### Before using package
Only works at Windows OS(Dependancy of EEG device).
Set the date display setting to yyyyy-MM-dd.
Set the time display setting to HH:mm:ss.

### Full pipeline(experiment to analysis)

* ERP task
```shell
./scripts/erp_combination.sh
```

* ERDS task
```shell
./scripts/erds_grap.sh
```

* SSVEP task
```shell
python ssvep_quiz.py
```

* ERP_SSVEP task
```shell
python erp_ssvep_speller.py
```