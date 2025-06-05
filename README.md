
# 🌙 Dream Detector

A fun AI-powered web application that classifies your dreams using machine learning. Just enter your dream description, and get a possible category—because dreams are worth decoding!

## 💡 Features

- 🧠 Classifies dreams into categories like Happy, Sad, Adventure, Scary, etc.
- 💬 Simple and intuitive UI
- ⚙️ Built with Flask (Python backend) + HTML/CSS frontend
- 🌐 Deployed with GitHub Pages (frontend) and Flask locally (backend)

## 🚀 Demo

Try it here: [https://rashi7903.github.io/dream-detector/](https://rashi7903.github.io/dream-detector/)  
(Note: For full functionality, run the backend locally.)

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Machine Learning:** Scikit-learn / custom model
- **Deployment:** GitHub Pages (Frontend), Localhost (Backend)

## 🖥️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Rashi7903/dream-detector.git
cd dream-detector
````

### 2. Set Up Python Environment

Make sure Python 3.10+ is installed.

```bash
pip install -r requirements.txt
```

### 3. Run the Flask App

```bash
python app.py
```

The server will run on `http://127.0.0.1:5000`

### 4. Open in Browser

Visit the local site in your browser to use the full application.

> ⚠️ GitHub Pages only hosts static files. Flask (backend) must run locally or be deployed via a cloud provider like Render, Heroku, etc., to support dream classification.

## 📁 Project Structure

```
dream-detector/
├── templates/
│   └── index.html         # Main HTML UI
├── static/
│   └── style.css          # Stylesheet
```

## 📸 Screenshots

SAMPLE DREAM 1:-
Dream Description: I was standing on a cliff overlooking a vast ocean. The sky was a mix of vibrant colors, like a sunset. Suddenly, I felt a strong wind pushing me towards the edge, and I was terrified of falling. I tried to step back, but my feet felt glued to the ground. Just then, I saw a giant eagle soaring above me, and it seemed to be watching me. I felt a sense of calm wash over me as I focused on the eagle. Eventually, the wind died down, and I was able to step back safely.

Details:

Age at the time of the dream: 25
Gender: Female

![image](https://github.com/user-attachments/assets/8161ccbe-064c-4f20-a481-1a0f473a117e)

SAMPLE DREAM 2:-
Dream Description: I found myself in a large, unfamiliar library filled with towering shelves of books. The atmosphere was quiet, and the air smelled of old paper. I was searching for a specific book that I couldn't remember the title of, but I felt it was very important. As I wandered through the aisles, I noticed that some books were glowing softly. I reached out to touch one, and as I did, the entire library began to shake, and the lights flickered. I felt a mix of excitement and fear, and then I woke up just as a book fell off the shelf.

Details:

Age at the time of the dream: 30
Gender: Male

![image](https://github.com/user-attachments/assets/f5862df3-5668-4e14-ae98-1d8c3ddef679)

## 🧠 Future Improvements

* Add database for saving dream logs
* Train a deeper NLP model using LSTM or Transformers
* Deploy backend on cloud for full online use

## 🙋‍♀️ Author

**Rashi Kumari**
📫 [@Rashi7903](https://github.com/Rashi7903)

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

✨ *Let your dreams speak—because even the wild ones make sense to a machine.* ✨
