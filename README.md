# 🍲 Recipe Management Website
A **Flask + MySQL recipe management web app** to create, share, and organize recipes online.  
Features include **user authentication**, **image uploads**, **allergen tracking**, and **veg/non-veg categorization**, providing an interactive, collaborative cooking platform.

---

## 🚀 Key Features
- **User Authentication**: Secure user registration and login system.  
- **Recipe Management**: Add, view, and categorize recipes as **vegetarian** or **non-vegetarian**.  
- **Allergen Tracking**: Specify allergens for each recipe for safer meal planning.  
- **Image Uploads**: Upload high-quality recipe images with **Flask-Uploads**.  
- **Dynamic Dashboard**: Responsive UI built with **HTML, CSS, Bootstrap**, and **Jinja templates**.

---

## 🛠️ Technologies Used
- **Backend**: Flask (Python) + MySQL (with `mysql-connector` for seamless database connectivity)  
- **Frontend**: HTML, CSS, and Bootstrap for a mobile-friendly, intuitive interface  
- **File Management**: Flask-Uploads for recipe image storage  
- **Version Control**: Git & GitHub for source code management and collaboration

---

## 🧑‍🍳 Getting Started

### Prerequisites
- Basic Python knowledge (Flask framework)  
- Familiarity with HTML, CSS, and Jinja templating  

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/ShreyaVijaykumar/RECIPE-MANAGEMENT-WEBSITE.git
   ```
   
2. **Navigate to the project directory**
   ```bash
   cd recipe_manager
   ```
   
3. **Set up a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   ```
   
4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   
5. **Set up the database**
- Create a MySQL database
- Update config.py with your database credentials
- *Initialize with:*
  ```bash
  python setup_db.py
  ```

6. **Start the application**
  ```bash
  flask run   # or python app.py
  ```

7. **Open http://127.0.0.1:5000/**
 in your browser or corresponding port

---

📂 Project Structure

## 📂 Project Structure

```text
recipe-management-system/
├── templates/
│   ├── index.html
│   ├── add_recipe.html
│   ├── login.html
│   ├── profile.html
│   ├── register.html
├── static/
│   ├── style.css
├── app.py
├── recipes.db
├── README.md
```

---

🤝 Contributing

- Fork the repository
1) Create a feature branch
  ```bash 
  git checkout -b feature-name
  ```

2) Commit changes
  ```bash
  git commit -m 'Add new feature'
  ```

3) Push the branch
  ```bash
  git push origin feature-name
  ```
4) Open a pull request.

---

👥 Contributors

- [Shreya Vijaykumar](https://github.com/ShreyaVijaykumar)  
- [Shaik Arbaaz](https://github.com/ShaikArbaaz)

---

## 🔎 SEO & Discoverability

**Trending Keywords:**  
Flask recipe app • MySQL recipe database • Python recipe website • Recipe management system • Online recipe sharing platform • Flask cooking app • Recipe organizer web app

**Niche & Long-Tail Phrases:**  
Open-source recipe management tool • Responsive cooking website with image upload • Allergen-friendly recipe manager • Flask Bootstrap web application • DIY recipe catalog using Python • Food blogging web app with database • Vegetarian and non-vegetarian recipe tracker

**Suggested GitHub Topics/Tags:**  
`flask` `mysql` `python` `recipe` `cooking` `food` `webapp`  
`recipe-management` `recipe-sharing` `flask-webapp` `bootstrap` `open-source`

