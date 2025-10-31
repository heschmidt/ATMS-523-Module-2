[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/h-dtmO0d)
# ATMS-523-Module-2

Install required libraries using the `environment.yml` file.  `mamba install environment.yml` then mamba activate `xarray-climate`.

The Homework assignment can be completed in a new jupyter notebook that you commit to this repository.

The examples from lecture 3 and 4 are here also.

Make sure you install software as we did in the check in:
   ```bash
   mamba env create --prefix $HOME/envs/xarray-climate -f environment.yml
   mamba activate $HOME/envs/xarray-climate
   ```
   or with pip:
   ```bash
   python -m venv .venv && source .venv/bin/activate
   pip install -r requirements.txt
   ```

   and use this environment when running the codes and for your homework.