🛡️ Automated GRC Risk Heatmap
Overview
This project transforms traditional, static GRC (Governance, Risk, and Compliance) risk registers into dynamic, actionable visualizations. Using Python and Google Colab, I developed a system that categorizes security threats based on Impact and Likelihood, providing a "single pane of glass" view for cybersecurity stakeholders.

🚀 The Business Problem
In many organizations, risk data is buried in massive spreadsheets. This makes it difficult for CISOs and IT managers to:

Identify high-priority threats at a glance.

Justify security budget allocation based on data.

Track how specific threats like Ransomware or Phishing move across the risk landscape.

🛠️ Technical Stack
Language: Python.

Environment: Google Colab (Cloud-based execution for accessibility and reproducibility).

Libraries: * Pandas: For data manipulation and cleaning.

Seaborn/Matplotlib: For generating the heatmap and annotation layers.

NumPy: For matrix calculations.

📈 Key Features
Custom Annotations: Unlike standard heatmaps, this tool labels specific threats directly on the grid for immediate context.

Inverted Y-Axis: Designed for professional GRC reporting where the highest impact risks are displayed at the top.

Lightweight Design: Optimized to run on any hardware (tested on a 2012 MacBook Air) via cloud compute.

📝 How to Use
Open the .ipynb file in Google Colab.

Upload your risk register as a CSV or use the built-in synthetic dataset.

Run the cells to generate your updated Risk Heatmap.


<img width="842" height="707" alt="heat_output" src="https://github.com/user-attachments/assets/39f7d865-aab4-4322-a2af-47e547a18f9d" />
<img width="649" height="553" alt="heat_map" src="https://github.com/user-attachments/assets/ad7a3a83-d7ea-41c1-80a0-dfd640b125be" />




<img width="842" height="707" alt="heat_output" src="https://github.com/user-attachments/assets/25da70aa-515e-4391-8f9f-90a6ccb3a06c" />
