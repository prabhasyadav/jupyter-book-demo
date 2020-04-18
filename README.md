# Jupyter Book

## Project Installation

### Setting up environment

```bash
# Clone the repository
git clone https://github.com/prabhasyadav/jupyter-book-demo.git

# Go to project directory
cd jupyter-book-demo

# Setup the virtual environment
python3 -m venv venv


# Activate the environment
source venv/bin/activate # (For Linux)
#          OR
.\venv\Scripts\activate # (For Windows)

# Install all the dependecies
pip3 install -r requirements.txt
make install
```

### Run the project

```bash
# Go to project directory
cd jupyter-book-demo

# Activate the environment
source venv/bin/activate # (For Linux)
#    			OR
.\venv\Scripts\activate # (For Windows)

# Build the project website (works only when in root folder)
make book

# Host the book locally
make serve
```
