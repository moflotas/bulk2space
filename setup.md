# How to setup the project

## Setup for python3.9 (other versions may not work)

1. Clone repository
   - `git clone git@github.com:moflotas/bulk2space.git`
2. If not already installed, install `python3.9`
   - For `apt` packet manager `sudo apt install python3.9`
3. If not already installed, install `venv`
   - For `apt` packet manager `sudo apt install python3.9-venv`
4. In the root directory of the repository create and activate venv
   - `python3.9 -m venv venv`
   - `source venv/bin/activate`
5. Install requirements
   - `pip install -r requirements.txt`
6. **(FOR INFORMATION)** To deactivate the venv, use `deactivate` or `source deactivate` in the terminal

If you did everything correctly, you should be able to execute cells in the `jupyter notebooks` `demo1.ipynb` and `demo2.ipynb` and see the results.

Otherwise, you can try to rollback to the original state of the repository by using `git reset --hard HEAD` in the root directory of the repository and again.

> Note usage of `venv` is optional, but recommended. You may encounter many version conflicts with other python packages if you do not use `venv`, especially with `deep-forest`, `numpy` and `matplotlib`.
