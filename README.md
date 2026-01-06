# processdataAIC2026

## Setup Conda Environment
### Download Miniconda
Download the Miniconda distribution from: 
👉 `https://www.anaconda.com/download/success`



### Install Miniconda
Run the downloaded `.exe` file and complete the installation.



### Initialize Conda for PowerShell
Open CMD and run:

```bash
conda init powershell
```



### Check for available resources 

```bash
conda update conda       
conda search "^python$" 
```


### Create environment 

```bash
conda create -p aic2026 python=3.12.4
conda activate aic2026
```

### Show env list 

```bash
conda env list
```



### Activate the Virtual Environment

```bash
conda active aic2026
```



### Install packages
We can use either `pip` or `conda` for installation interface

```bash
conda install numpy pandas ...
```

```bash
pip install numpy ...
```

---