# Wikipedia Data Project: Chemical Elements

### 🧪 Overview
This project scrapes and analyzes data from Wikipedia’s **List of Chemical Elements**.  
It focuses on cleaning messy numeric data, computing 15 scientific KPIs, and visualizing periodic trends across all 118 elements.

---

### 📊 Key Features
- Live web scraping using **Pandas** (`read_html`)  
- Data cleaning with **regex** and numeric conversions  
- Analysis of **15 KPIs** grouped into 5 categories:
  1. Periodic Table Structure  
  2. Atomic & Physical Properties  
  3. Thermal & Energy Behavior  
  4. Natural Abundance & Availability  
  5. Chemical Reactivity & Bonding Behavior  
- Visualizations created with **Matplotlib** and **Plotly**

---

### 📂 Files Included
- `chemical_elements_analysis.ipynb` – Jupyter Notebook with full code  
- `cleaned_elements.xlsx` – cleaned dataset  
- `Chemical_Elements_Project_Styled.pptx` – PowerPoint summary with visual KPIs  
- `requirements.txt` – Python dependencies list  

---

### ⚙️ How to Run
1. **Clone this repository:**
   ```bash
   git clone https://github.com/AymanBerri/Wikipedia-Elements-Analysis.git
   cd wikipedia-elements-analysis
   ```

2. **Create a virtual environment (recommended):**
  ```bash
  python -m venv venv
  source venv/bin/activate      # On Mac/Linux
  venv\Scripts\activate         # On Windows
  ```


3. **Install dependencies:**
  ```bash
  pip install -r requirements.txt
  ```

4. **Run the notebook:**
  ```bash
  jupyter notebook
  ```

Open chemical_elements_analysis.ipynb to explore the code and visualizations.
