# processdataAIC2026

## Setup Conda Environment
### Step 1: Download Miniconda
Download the Miniconda distribution from: 
👉 `https://www.anaconda.com/download/success`

---

### Step 2: Install Miniconda
Run the downloaded `.exe` file and complete the installation.

---

### Step 3: Initialize Conda for PowerShell
Open CMD and run:

```bash
conda init powershell
```

---

### Check for available resources 

```bash
conda update conda       
conda search "^python$" 
```

---

### Create environment 

```bash
conda create -n aic2026 python=3.12.4
conda activate aic2026
```
