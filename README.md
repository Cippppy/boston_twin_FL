![alt text](images/bostontwin.png "Boston Twin")

# BostonTwin
Repository for the BostonTwin dataset API.

## Requirements
The basic requirements for the BostonTwin API are based on those of [Sionna](<https://nvlabs.github.io/sionna/>), plus some georeferencing libraries:
1. `python>=3.8`
2. `geopandas`
3. `open3d`
4. `contextily`

and the corresponding dependencies.

We provide a requirement file for pip (`requirements.txt`) and conda (`environment.yaml`) to create a Python virtual environment with all the dependencies.

## Quickstart - Windows
1. Clone this repo
2. Download the BostonTwin dataset from <https://repository.library.northeastern.edu/files/neu:h989t1201> into the `bostontwin` folder. Download the file from the linked website and the .zip into the `boston_twin_fl folder`. Then, extract the files from the .zip and the `bostontwin` folder should be created.
3. Install the requirements. 
```powershell
python -m venv envs/bostwin
```
```powershell
envs\bostwin\Scripts\Activate.ps1
```
```powershell
pip install -r requirements.txt
```
4. Install LLVM.

5. Run the [bostontwin_demo](<https://github.com/wineslab/boston_twin/blob/main/bostontwin_demo.ipynb>) Jupyter Notebook to see how to use BostonTwin, the Digital Twin of Boston!
6. Refer to the [documentation](<https://wineslab.github.io/boston_twin/src/classes/BostonTwin.html>) for additional information.