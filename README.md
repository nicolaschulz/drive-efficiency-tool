# Energy Calculation Tool for Drive Systems

This tool calculates the energy consumption and annual energy cost of a drive system based on a load profile and efficiency data.

✅ Upload your Excel files (efficiency data + load profile)  
✅ Enter additional parameters (e.g. energy price)  
✅ Calculate energy consumption, costs and losses

---

## ▶️ Launch the tool online

Right-click on the [![Binder](https://mybinder.org/badge_logo.svg)] links below to open the tool in a new browser tab.  

**Note:** The tool is based on a jupyter Notebook and is opened via [MyBinder](https://mybinder.org/). Please be patient; the loading time can be approx. 1 minute.

### Calculation tool based on power and time data

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nicolaschulz/drive-efficiency-tool/main?urlpath=voila/render/energy_calculator1.ipynb)

### Calculation tool according to EN 61800-9-1 (shaft speed and torque)

---

## 📂 Example files

If you want to test the tool, you can use sample Excel files in the `data/` folder.

---

## 🧰 Installation (optional, local)

```bash
git clone https://github.com/nicolaschulz/drive-efficiency-tool.git
cd drive-efficiency-tool
pip install -r requirements.txt
voila tool_notebook.ipynb
