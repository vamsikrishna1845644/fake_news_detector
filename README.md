# **Fake News Detection Webapp** 📰

**A webapp for predicting whether the text of a news article is true or fake.**


---

## **Motivation 💡**

Fake news is a problem that emerged with the modern information age. It spreads like a virus across networks and provides nothing but disinformation.

Even though some companies invest heavily in this field, this project is a **personal approach** to help people detect fake news, providing a simple and accessible tool.

---

## **How it Works ⚙️**

This is a **Machine Learning oriented project**. The webapp allows users to input news text, and predicts whether the news is true or fake.
---

## **Datasets 📊**

For training and testing the model, the following datasets were used:

* **'Fake News' InClass Prediction Competition**
* **'Fake and Real News Dataset'** by Clément Bisaillon

---

## **Tech Stack 🛠️**

* **Backend**: Django
* **Machine Learning**: Scikit-learn, NLP preprocessing
* **Frontend**: HTML, CSS, Bootstrap
* **Database**: SQLite (default)
* **Deployment**: Heroku

---

## **Installation & Running Locally 🚀**

**Python Version:** 3.7.10

**1. Clone the repository**

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

**2. Create a virtual environment (Anaconda/Miniconda)**

```bash
conda env create -f environment.yml
conda activate your-env-name
```

**3. Or using pip**

```bash
pip install -r requirements.txt
```

**4. Run the server**

```bash
python manage.py runserver
```

**5. Open your browser**
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## **Usage 🖱️**

* Input the text of a news article.
* Click **Predict** to see if the news is True or Fake.
* Use responsibly to verify news before sharing.

---



---

## **Contributing 🤝**

* Fork the repository.
* Create a new branch: `git checkout -b feature/YourFeature`.
* Commit your changes: `git commit -m 'Add some feature'`.
* Push to the branch: `git push origin feature/YourFeature`.
* Open a pull request.

---

## **License 📄**

This project is licensed under the copyright.
