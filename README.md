# H_lloyd-container-optimization
Container repositioning optimization analysis - Technical case study using Python, NetworkX, and data analysis


# Container Repositioning Optimization Analysis

## 🚢 Project Overview
Technical case study analyzing empty container repositioning efficiency for a major shipping company. This project identifies operational inefficiencies in container movements and provides actionable insights for logistics optimization.

## 📊 Key Achievements
- Processed and cleaned **475,986** container movement records
- Identified **3,198 circular movements** causing operational inefficiencies  
- Detected **4,612 inefficient routing patterns** with unnecessary stops
- Removed **230,266 duplicate records** (48% data quality improvement)

## 🔧 Technical Implementation
- **Data Processing:** Pandas for large-scale data cleaning and validation
- **Network Analysis:** NetworkX for graph-based routing optimization
- **Pattern Detection:** Custom algorithms for identifying circular movements and routing inefficiencies
- **Performance:** Optimized processing using caching and vectorization

## 📈 Analysis Components
1. **Data Quality & Cleaning**
   - Duplicate detection and removal
   - Location validation against master data
   - Missing value handling

2. **Flow Analysis**
   - Surplus/deficit location identification
   - Conversion rate analysis (System vs User-generated actions)
   - Equipment type flow patterns

3. **Inefficiency Detection**
   - Circular movement detection using graph cycles
   - Routing inefficiency analysis (indirect vs direct routes)
   - Time-window based pattern recognition (4-week periods)

## 🛠️ Technologies Used
- Python 3.10
- Pandas & NumPy (Data Processing)
- NetworkX (Graph Analysis)
- Matplotlib & Seaborn (Visualization)
- Jupyter Notebook (Interactive Analysis)

## 📁 Repository Structure
- `deficit_action_plan_notebook.ipynb` - Complete analysis notebook
- `requirements.txt` - Python dependencies
- `images/` - Generated visualizations and network graphs

## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/adheir01/hapag-lloyd-container-optimization.git

# Install dependencies
pip install -r requirements.txt

# Open notebook
jupyter notebook deficit_action_plan_notebook.ipynb
