# ✈️ Aviation Accident Risk Analysis (1962–2023)

This project presents a comprehensive analysis of aviation accidents between 1962 and 2023. The goal is to identify low-risk aircraft types, uncover accident trends, and offer data-driven recommendations for businesses in the aviation industry.

## Project Overview

This data science project explores accident data to answer key questions around aviation safety, aircraft reliability, and environmental factors contributing to incidents. It leverages Python, Pandas, and visualization libraries to drive insight and support strategic aviation decisions.

## Project Structure

The project repository is organized as follows:
- `README.md`: Project description, setup instructions, and key findings.
- `aviation_accident_analysis.ipynb`: Main Jupyter Notebook with full analysis and visualizations.
- `aviation_accident_analysis_presentation.pptx`: Stakeholder-ready presentation of insights.
- `data/`: Contains raw and cleaned datasets.
- `images/`: Visual assets used in the notebook and documentation.
  - `911.jpeg`
  - `PlaneCrushing.jpeg`
  - `PlaneCrushing1`

## Instructions

1. **Clone the Repository**  
Open your terminal and run:
```bash
git clone https://github.com/OndiekiFrank/aviation-accidents-analysis.git
cd aviation-accidents-analysis
```

2. **Create and Activate Conda Environment**  
Create a new Python environment and activate it:
```bash
conda create -n aviation-analysis python=3.10 -y
conda activate aviation-analysis
```

3. **Install Dependencies**  
Install the required libraries:
```bash
conda install pandas matplotlib seaborn plotly jupyter -y
```

4. **Launch Jupyter Notebook**  
Run the notebook:
```bash
jupyter notebook
```

## 📈 Results & Insights

🛩️ Single-engine land aircraft have historically higher incident rates.  
⛅ A significant portion of accidents are caused by pilot error, weather conditions, or mechanical failure.  
✈️ Commercial and cargo flights tend to be safer than private or instructional flights.  
📅 Peak accident periods correspond to early decades and seasonal weather patterns like winter and fog.  
📓 For full insights, see: `aviation_accident_analysis.ipynb`

## 🎯 Business Recommendations

✅ Invest in multi-engine aircraft with strong safety records.  
🚫 Avoid aircraft models with frequent recurrence in accident reports.  
🧠 Provide robust pilot training for adverse weather conditions.  
📊 Use heatmaps and historical trends to plan safer routes.

## 🙋 About the Author

Hi! I'm Frankline Ondieki, a passionate Data Scientist based in Nairobi, Kenya.  
Currently studying at Moringa School, I use data to tell compelling stories and drive decision-making.

📧 Email: ondiekifrank021@gmail.com  
🔗 LinkedIn: [Frankline Ondieki](https://www.linkedin.com/in/franklineondieki)  
🌍 GitHub: [OndiekiFrank](https://github.com/OndiekiFrank)

## ⭐️ Show Your Support

If you found this project useful or insightful:
- 🌟 Star this repository
- 🐛 Report bugs or suggest features via issues
- 🤝 Connect with me on LinkedIn

## 📌 Future Enhancements

🖥️ Build an interactive Streamlit dashboard  
🗺️ Add geospatial analysis for crash site mapping  
🌦️ Integrate weather APIs for real-time simulation  
📦 Package project as a Docker-based microservice

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.