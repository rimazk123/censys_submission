## Setup Instructions

First, clone the repository 

```bash
git clone https://github.com/rimazk123/censys_submission
```

Setup and start your virtual environment

```bash
python -m venv env
source env/bin/activate
```

Install the dependencies
```bash
pip install -r requirements.txt
```

Put your censys uid and secret in the .env file
```
UID=your_uid
SECRET=your_secret
```

Now run the script with the following command, and your the results will be in results.csv
```bash
python script.py
```
