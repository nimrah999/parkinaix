

# 🧠 Detecting Parkinson's Disease through Spiral Images.
– A Reliable AI Model with 80% Accuracy

---

## 🌍 About the Project

**Parkinaix** is a simple yet powerful AI model that helps detect **Parkinson’s Disease (PD)** using **spiral and wave sketches drawn by hand**.
It is based on the research paper *“Automated Parkinson’s Disease Detection Based on Handwriting Movement”* by **Rigas et al.**, which showed that a person’s hand movements can reveal early signs of Parkinson’s disease.

This project uses **Google’s Teachable Machine**, a no-code platform, to train the model. The trained model achieves **83% accuracy** in identifying Parkinson’s-related movement patterns.

---

## 🧬 Background and Research Context

Parkinson’s Disease is a **neurodegenerative disorder** that affects brain cells responsible for movement. It leads to **tremors, stiffness, slowness**, and difficulty in writing or drawing.
Doctors often use **handwriting tests**, like drawing spirals or waves, to observe motor control and detect early symptoms.

Over the years, researchers have found that analyzing these sketches with **machine learning** can reveal subtle movement changes that humans may miss.
Parkinaix builds on this idea — combining **medical research** with **AI-powered image recognition** to create a fast and non-invasive detection tool.

---

## ⚙️ Key Highlights

* 🌀 Detects Parkinson’s disease using **spiral and wave sketch images**.
* 🧠 Uses **Teachable Machine**, Google’s drag-and-drop tool for ML training.
* 📊 Achieves **83% accuracy** on test datasets.
* ⚡ Fast, lightweight, and easy to integrate into apps.
* 🧩 Can be retrained with your own dataset for improved performance.

---

## 🚀 How It Works

1. Collect a dataset of **hand-drawn spirals and waves** (from patients and healthy subjects).
2. Upload and train the dataset on **Teachable Machine**.
3. Export the trained model.
4. Run it locally with **Streamlit** to test or deploy online.

---

## 🧰 Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/<your-username>/Parkinaix
cd Parkinaix
```

### Step 2: Install Dependencies

Make sure Python 3 is installed, then run:

```bash
pip install -r requirements.txt
```

### Step 3: Run the App

```bash
streamlit run streamlitApp.py
```

---

## 🧪 Tools and Technologies

* **Python 3** – for building and running the project
* **Teachable Machine** – for training the AI model without coding
* **Streamlit** – for creating a simple web interface to test predictions

---

## 💡 What is Teachable Machine?

**Teachable Machine** is a project by **Google** that lets anyone create and train machine learning models without writing code.
You can upload images, sounds, or poses, and the platform will train a model that can recognize patterns in new data.
In Parkinaix, it’s used to classify spiral and wave drawings as *Parkinson’s* or *Healthy*.

---

## 🎨 Streamlit Theme Configuration

```ini
[theme]
base = "dark"

[browser]
gatherUsageStats = false
```

---

## 📈 Model Performance

* **Confusion Matrix** – Evaluates correct vs. incorrect predictions
* **Accuracy per Class** – Shows how well the model performs for each label
* **Accuracy per Epoch** – Displays model improvement per training round
* **Loss per Epoch** – Indicates how much the model’s predictions improved

---

## 🌐 Deployment Resources

* [Deploy on Streamlit Cloud](https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app)
* [30 Days of Streamlit Guide](https://30days.streamlit.app/)
* [Advanced Configuration Docs](https://docs.streamlit.io/library/advanced-features/configuration)

---

## 📚 Research References

* Rigas, G., Tzallas, A. T., et al. *Automated Parkinson’s Disease Detection Based on Handwriting Movement.*
* Saboor, A., et al. *Spiral Drawing Test for Parkinson’s Disease Detection Using AI-Based Analysis.*
* Google Teachable Machine Documentation – [https://teachablemachine.withgoogle.com/](https://teachablemachine.withgoogle.com/)

---

## ⭐ Acknowledgment

This project is inspired by ongoing research in **AI-assisted healthcare** and **neurological disease detection**.
Special thanks to the research community working toward **early diagnosis** and **improving patient lives** through technology.

---

## 💫 Support

If you found this helpful, please **star ⭐ this repository**.
Your support encourages more open-source health-tech projects like Parkinaix!

---

Would you like me to make this version sound **more academic (for portfolio or publication)** or keep it **more casual and beginner-friendly (for GitHub readers and students)?**
