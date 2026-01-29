<div align="center">

# ELSAYED ASHRAF BAKRY

**Electrical Communications & Electronics Engineering**  
*Alexandria University*

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Machine+Learning+Engineer;Embedded+Systems+Developer;Data+Engineering+Enthusiast;TinyML+%26+Edge+AI+Researcher" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/elsayed-ashraf-bakry)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sayedworkacc@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ExpiredEng)

</div>

---

## 🎯 MISSION STATEMENT

Bridging the **physical** and **digital** worlds through intelligent systems. From sensor circuits to cloud pipelines, I build end-to-end solutions that transform raw data into actionable intelligence.

```python
class Engineer:
    def __init__(self):
        self.name = "Elsayed Ashraf Bakry"
        self.role = "ML & Embedded Systems Engineer"
        self.location = "Alexandria, Egypt"
        self.interests = ["TinyML", "Edge AI", "IoT", "Data Engineering"]
        
    def current_focus(self):
        return {
            "learning": "Microsoft Azure Data Engineering",
            "researching": "Optics & Photonics @ Virginia Tech Collab",
            "building": "Low-level ML implementations in C"
        }
```

---

## 🛠️ TECHNICAL STACK

<table>
<tr>
<td width="50%" valign="top">

### **Languages & Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-E16737?style=flat-square&logo=mathworks&logoColor=white)

### **AI & Machine Learning**
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)

</td>
<td width="50%" valign="top">

### **Data & Cloud**
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

### **Embedded & Hardware**
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFD400?style=flat-square&logo=ni&logoColor=black)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)

### **Developer Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

</td>
</tr>
</table>

---

## 💼 FEATURED PROJECTS

### 🧠 **Handwritten Digit Recognition in Pure C**
> *Building ML algorithms from scratch - no libraries, just raw code*

**The Challenge**: Implement a complete machine learning pipeline using only C programming language  
**The Solution**: Built custom data structures, feature extraction, and classification algorithms from the ground up

- ⚡ **Zero Dependencies**: Pure C implementation with manual memory management
- 🔬 **Educational Deep Dive**: Understanding ML at the lowest level for embedded applications
- 🎯 **Focus**: Foundation for TinyML and edge computing research

```c
// Example: Low-level neural network forward pass
void forward_pass(Layer* layer, float* input, float* output) {
    for(int i = 0; i < layer->neurons; i++) {
        output[i] = 0;
        for(int j = 0; j < layer->inputs; j++) {
            output[i] += input[j] * layer->weights[i][j];
        }
        output[i] = activate(output[i] + layer->bias[i]);
    }
}
```

**Tech Stack**: `C` `Manual Memory Management` `Custom Algorithms`

---

### 🏥 **Smart ICU Patient Monitoring System**
> *Real-time biomedical data acquisition and intelligent alerting*

**The Challenge**: Monitor critical patient vitals and environmental parameters with high reliability  
**The Solution**: Integrated hardware sensor network with intelligent software interface

- 📊 **Multi-Sensor Integration**: Heart rate, SpO2, temperature, humidity, and more
- 🚨 **Automated Alert System**: Real-time threshold monitoring with visual/audio alerts
- 💾 **Continuous Logging**: Persistent data storage for medical analysis
- ✅ **Validated Accuracy**: Sensor calibration and end-to-end testing protocols

**Tech Stack**: `LabVIEW` `Biomedical Sensors` `Real-Time Systems` `Data Acquisition`

---

### 📊 **Customer Churn Prediction Web App**
> *End-to-end ML deployment for telecom analytics*

**The Challenge**: Predict customer churn to enable proactive retention strategies  
**The Solution**: Full-stack ML application with feature engineering and interactive deployment

- 🔍 **Feature Engineering**: Created predictive features from raw telecom data
- 🎯 **Model Optimization**: Compared classification algorithms (accuracy, precision, recall, ROC-AUC)
- 📈 **Interactive Visualizations**: Real-time predictions with Streamlit dashboard
- 🚀 **Production Ready**: Deployed web application for business insights

**Tech Stack**: `Python` `Scikit-learn` `Streamlit` `Pandas` `Matplotlib`

---

### ❤️ **Heart Disease Risk Prediction Pipeline**
> *Clinical ML pipeline for cardiovascular risk assessment*

- 🧹 **Data Preprocessing**: Handled missing values, outliers, and feature scaling
- 🎨 **Visualization**: Matplotlib & Seaborn for clinical data exploration
- ⚖️ **Model Comparison**: Evaluated multiple algorithms for medical prediction
- 📋 **Medical Context**: Risk stratification for healthcare decision support

**Tech Stack**: `Python` `Scikit-learn` `Pandas` `Seaborn` `Medical Data`

---

## 🎓 EDUCATION & TRAINING

### 🏛️ **Bachelor of Engineering** - Electrical Communications & Electronics
**Alexandria University** | *Sep 2023 – Jun 2028 (Expected)* | **GPA: 3.64/4.0**

### 📚 **Professional Training**

<table>
<tr>
<td width="33%">

**🔷 DEPI Track**  
AI & Data Science  
*Microsoft Data Engineer*

- Azure Cloud Services
- SQL & Data Modeling
- ETL Pipelines
- DevOps & CI/CD

</td>
<td width="33%">

**🎯 GTC ML Track**  
Genius Technology Center

- 60-Hour Intensive
- ML/DL Fundamentals
- Model Deployment
- Aug–Sep 2025

</td>
<td width="33%">

**🚀 Microsoft Camp**  
Sprints x Microsoft

- 40-Hour Training
- AI & ML Workflows
- Hands-on Projects
- Summer 2025

</td>
</tr>
</table>

---

## 🔬 RESEARCH EXPERIENCE

### **Research Assistant** | Optics Research Lab
**Virginia Tech Collaboration** | *Jan 2025 – Present*

- 🔭 Conducting optical measurements and system characterization experiments
- ⚙️ Set up and calibrated 3+ experimental optical analysis systems
- 📊 Data analysis using MATLAB and Python for research insights
- 🤝 Structured collaboration with faculty mentors

---

## 📊 GITHUB ANALYTICS

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ExpiredEng&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF" height="170" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ExpiredEng&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ExpiredEng&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF" height="170" />

</div>

---

## 🎯 CORE COMPETENCIES

```yaml
Machine Learning:
  - Classification & Regression Models
  - Feature Engineering & Selection
  - Model Evaluation & Optimization
  - End-to-End ML Pipelines
  
Embedded Systems:
  - Arduino & Microcontroller Programming
  - Sensor Integration & Calibration
  - Real-Time Data Acquisition
  - Hardware-Software Co-Design
  
Data Engineering:
  - SQL Query Design & Optimization
  - Cloud Data Storage (Azure)
  - ETL Pipeline Development
  - Data Modeling & Transformation

Signal Processing:
  - Digital Signal Analysis
  - MATLAB/Python Implementation
  - Biomedical Signal Processing
  - Optical System Characterization
```

---

## 🌐 ACTIVITIES & INVOLVEMENT

### **IEEE Student Member** | Hardware Projects Team
*Jan 2024 – Present*

- 🔌 Arduino-based embedded systems prototyping
- 🛠️ Multi-sensor integration and testing
- 🔍 Circuit debugging with simulation tools
- 🤝 Collaborative engineering project development

---

## 💡 WHAT I'M CURRENTLY WORKING ON

```javascript
const currentProjects = {
    research: "Optical system characterization & data analysis",
    learning: "Microsoft Azure cloud data engineering",
    exploring: "TinyML implementations for edge devices",
    building: "Low-level ML in C for embedded systems"
};
```

---

## 📫 LET'S CONNECT

I'm always interested in discussing:
- 🤖 **TinyML & Edge AI** applications
- 🔬 **Research collaborations** in optics, embedded ML, or IoT
- 💼 **Opportunities** in ML engineering or embedded systems
- 💡 **Open source projects** at the hardware-software interface

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/elsayed-ashraf-bakry)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sayedworkacc@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/ExpiredEng)

---

*"From silicon to software, building intelligent systems that matter"*

![Profile Views](https://komarev.com/ghpvc/?username=ExpiredEng&color=00D9FF&style=flat-square)

</div>
