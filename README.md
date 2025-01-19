# MachineWolf

A machine learning project built with Python and VS Code.

Inspired by Etienne Bernards
[Introduction to Machine Learning](https://www.wolfram.com/language/introduction-machine-learning/)

---

## Project Structure

```bash
📂 machinewolf/
├── 📂 env/     # Virtual environment
├── 📂 data/    # Raw or processed datasets
├── 📂 models/  # Saved models
├── 📂 src/     # Python scripts
│ ├── main.py           # Main entry point for the program
│ ├── preprocessing.py  # Data cleaning/preprocessing scripts
│ └── model.py          # ML model definition
├── requirements.txt    # List of dependencies
└── README.md           # Project description and setup instructions
```

---

## Installation and Setup

### Prerequisites

- Python 3.9 or higher
- Git
- VS Code

### Clone the Repository

```bash
git clone https://github.com/BongoSort/machinewolf.git
```

### Create a Virtual Environment

```bash
cd machinewolf

python -m venv env
```

### Activate the Environment

```bash
# On Windows:
.\env\Scripts\activate

# On macOS/Linux:
source env/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```
