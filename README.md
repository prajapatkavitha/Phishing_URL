🔐 Phishing URL Detection using Machine Learning
A web-based system that detects phishing URLs using machine learning models.
![video](https://drive.google.com/file/d/1odehsHOuwrobTADLO-LXRjT2-bBnq77a/view?usp=sharing)

🚀 Features
• Detects phishing vs. legitimate URLs with high accuracy.
• Built with machine learning (scikit-learn, TensorFlow).
• Django-based backend with HTML/CSS/JavaScript frontend.
• Real-time feature extraction and prediction.
• User-friendly web interface for input and results.

🛠 Tech Stack
• Python (NumPy, Pandas, scikit-learn, TensorFlow)
• Django (Web Framework)
• Frontend: HTML, CSS, JavaScript
• Visualization: Matplotlib
• IDE: VS Code / PyCharm

📁 Project Structure
![image](https://github.com/user-attachments/assets/b248d875-4d9e-45e5-ad36-4c2c10635ca1)




⚙️ How to Run
Run the server:
  python manage.py runserver
  Visit http://127.0.0.1:8000 in your browser.
  
🧪 How It Works
• User inputs a URL via the web form.
• Features are extracted from the URL (length, presence of '@', number of dots, etc.).
• ML model classifies the URL as Phishing or Legitimate.
• Result displayed instantly on the web page.

📌 Future Improvements
• Add URL scraping for real-time data.
• Improve model accuracy with deep learning.
• Deploy as an online web service using AWS/GCP.
