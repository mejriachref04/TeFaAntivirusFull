# TeFaAntivirusFull

🛡️ **Prototype Desktop Antivirus with AI Detection**  
**Python + PyQt5 + Machine Learning**

**Author:** Achref Mejri 

TeFaAntivirusFull is a **prototype antivirus application** designed for educational and research purposes. It demonstrates how static analysis, heuristics, and machine learning can be used to detect suspicious files on a PC.

**Key Features:**
- Scan **single files** or **entire folders** (recursive)
- Detect **suspicious files** using SHA256 signature matching, suspicious strings, PE imports heuristics, optional YARA rules, and AI-based anomaly scoring
- **Quarantine** suspicious files safely
- Detailed **scan logs** saved for review

**⚠️ Safety Warning:**  
This is a research/prototype project. **Do not scan real malware on your host machine**. Use an isolated VM for testing. Quarantine and logs are stored locally to prevent accidental execution of suspicious files.

**Installation:**
1. Clone the repository:
git clone https://github.com/mejriachref04/TeFaAntivirusFull.git
cd TeFaAntivirusFull

3. Create a virtual environment:
Windows (PowerShell):
python -m venv venv
.\venv\Scripts\Activate.ps1
Linux/macOS:
python3 -m venv venv
source venv/bin/activate

4. Install dependencies:
pip install --upgrade pip
pip install -r requirements.txt
If yara-python or pefile fail to install, the app still works without those features.

5. Run the application:
python main.py
 
 
python main.py
