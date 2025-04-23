Here’s a more polished and professional version of your `README.md` in English, with enhanced structure, clarity, and style, plus your custom support section added at the end:

---

# Automated Machine Learning Web Application

This project presents an **Automated Machine Learning (AutoML) Web Application**, developed using Python, YData-Profiling, PyCaret, and Streamlit. The app is designed to democratise access to machine learning by automating essential processes such as data profiling, preprocessing, model selection, training, evaluation, and export.

## 🔧 Technologies Used

### [Python](https://www.python.org/)
The application is built using Python—a powerful, flexible programming language widely adopted in data science and machine learning. Its extensive ecosystem supports rapid development and robust machine learning workflows.

### [YData-Profiling (formerly Pandas-Profiling)](https://pypi.org/project/pandas-profiling/)
This library facilitates **automated exploratory data analysis (EDA)**, allowing users to instantly generate comprehensive data profiles. These include overviews of data types, missing values, distributions, and correlations—empowering users to understand their datasets before modelling.

### [PyCaret](https://pycaret.org/)
PyCaret offers a **low-code environment** for training and deploying machine learning models. It simplifies tasks like feature selection, model comparison, and hyperparameter tuning. With its support for a wide range of algorithms, PyCaret enables users to build and benchmark models efficiently.

### [Streamlit](https://streamlit.io/)
Streamlit enables the creation of intuitive, interactive user interfaces for machine learning applications. Users can upload datasets, inspect data profiles, select modelling targets, configure model parameters, and train models—all within a sleek and minimalistic interface.

## 🚀 Key Features

- Drag-and-drop dataset upload
- Instant data profiling via YData-Profiling
- Automated model comparison and selection using PyCaret
- Easy export of trained models
- Intuitive, no-code interface via Streamlit

This application is ideal for both beginners and professionals who want to streamline the machine learning pipeline without writing extensive code. It provides a foundation for understanding model behaviour while speeding up the experimentation process.

## 🛠 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Automated-Machine-Learning-App
   ```

2. **Create a virtual environment**
   ```bash
   conda create -n automl python=3.9 -y
   conda activate automl
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the application**
   ```bash
   streamlit run app.py
   ```

## 🤝 Contributions

Contributions are welcome! Please follow the standard GitHub workflow:
- Fork the repository
- Create a new branch for your feature or fix
- Submit a pull request

## 📫 Contact

For inquiries, feedback, or suggestions, feel free to reach out.

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---
