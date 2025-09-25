# 🚗🔧 Car Damage Recognition – Streamlit

An interactive **car damage recognition** application built with **PyTorch** and **Streamlit**.  
This project demonstrates how to handle image data, train deep learning models, evaluate performance, and provide a user-friendly interface for predictions.

---

## 📂 Project Structure

```bash
car_damage_streamlit/
├── app.py                  # Streamlit app (UI)
├── requirements.txt        # Dependencies
├── README.md               # Documentation
├── .streamlit/config.toml  # Streamlit theme config
├── data/
│   ├── data.csv            # CSV file: image paths + labels
│   └── image/              # Image dataset
├── models/                 # Saved models & label mapping
└── src/                    # Core source code
    ├── data.py             # Dataset + DataLoader
    ├── model.py            # Model architecture (ResNet18)
    ├── train.py            # Training & evaluation loop
    ├── train_cli.py        # Command-line training script
    └── utils.py            # Utilities (metrics, seed, plots)
```
## ⚙️ Installation
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/car_damage_streamlit.git
cd car_damage_streamlit
```
2. Create a virtual environment (python 3.10+):
```bash
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate      # Windows
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Run:  
Run with streamlit
```bash
streamlit run app.py
```
Press the training button  
<img width="896" height="577" alt="image" src="https://github.com/user-attachments/assets/102d5ef6-2406-4792-93a8-ae2a3ed71d71" />  


## 🖼 Demos:

