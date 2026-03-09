# Lichtenberg
Physics II Optional Project

This project attempts to numerically simulate dielectric breakdown to generate Lichtenberg figures.

## Environment Setup

1. **Create and activate a virtual environment**  

```bash
python -m venv venv

# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

2. Convert environment.yml to requirements.txt (requires Conda)
```bash
conda env export -f environment.yml --no-builds | grep -v "^prefix:" > requirements.txt
```

3. Install dependencies in the virtual environment
```bash
pip install -r requirements.txt
```


## Authors

Created by:
- Donyl Alcantara
- Timothy Andal
- Rafael Castro
- Raphael Dancel
- Jessica Ng
- Kenneth Tan

Course: PHYS2326 – University Physics II
Institution: Asian Institute of Management