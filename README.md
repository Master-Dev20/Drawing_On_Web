# 🎨 Drawing App with Flask  

A simple web-based **drawing application** built with **Flask, HTML, CSS, and JavaScript**. Users can draw on a canvas, choose different brush colors, clear the canvas, and **save their artwork as a PNG image**.  

## 📌 Features  
✔ **Draw** on a canvas using the mouse.  
✔ **Select brush colors** (Black, Red, Blue, Yellow, Green).  
✔ **Clear the canvas** with one click.  
✔ **Download your drawing** as a PNG image.  

## 🚀 Installation & Setup  

### 📌 Prerequisites  
Ensure **Python 3** is installed on your machine.  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Master-Dev20/Drawing_On_Web 
cd Drawing_On_Web  
```  

### 2️⃣ Install Dependencies  
Create a virtual environment and install the required packages:  
```bash
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate  
pip install flask pillow  
```  

### 3️⃣ Run the Application  
Start the Flask server:  
```bash
python app.py  
```  
The app will be available at **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)**.  

## 📁 Project Structure  
```
📂 drawing-app-flask  
│-- 📂 static  
│   │-- style.css  # UI styles  
│   │-- script.js  # JavaScript logic  
│   │-- drawing.png  # Saved drawings (generated dynamically)  
│-- 📂 templates  
│   │-- index.html  # Frontend UI  
│-- app.py  # Flask backend  
│-- README.md  # Project documentation  
```  

## 🔗 API Endpoints  
| Route  | Method | Description |  
|--------|--------|-------------|  
| `/`    | GET    | Loads the drawing page |  
| `/save` | POST   | Saves and downloads the drawing as a PNG |  

## 🎨 Usage  
1️⃣ **Open the app** in your browser.  
2️⃣ **Draw** on the canvas using your mouse.  
3️⃣ **Select a color** for your brush.  
4️⃣ **Click "Clear"** to reset the canvas.  
5️⃣ **Click "Download"** to save your drawing as a PNG.  

💡 **Built with Flask & Love ❤️**  
