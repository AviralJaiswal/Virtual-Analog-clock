
# Analog Clock
An interactive and visually appealing **Analog Clock** built using **HTML, CSS, and JavaScript**.  
The clock displays the current system time in real-time with smoothly rotating hour, minute, and second hands.

This project is lightweight, responsive, and designed to demonstrate essential front-end concepts such as DOM manipulation, CSS transformations, JavaScript timing functions, and modern UI styling techniques like **Neomorphism**.

---

## 🌐 Live Demo

🔗 The website is deployed here:  
https://aviraljaiswal.github.io/Virtual-Analog-clock/

---

### *Features*:
* User-friendly
* Displays current Time
* Neomorphic Interface 
* Dark Mode ↔ Light Mode theme toggle  
* Smooth and accurate clock hand rotation
* Real-time hour, minute, and second hand movement
* Responsive design for different screen sizes   

## Website Demo:
![1](https://user-images.githubusercontent.com/61280281/85862463-6e0a9a00-b7df-11ea-806e-2ebbeda2ab0c.png)
![2](https://user-images.githubusercontent.com/61280281/85862468-6fd45d80-b7df-11ea-8142-435302297a22.png)
![3](https://user-images.githubusercontent.com/61280281/85862470-706cf400-b7df-11ea-8e31-90f2f8ae4a2e.png)

## *Technologies used*

- HTML5
- CSS3 (with Flexbox)
- Vanilla Javascript


## *References*
* For Fonts: [Google Fonts](https://fonts.googleapis.com/css2?family=Work+Sans:wght@300&display=swap)
* For Color Coordination: [w3schools](https://www.w3schools.com/colors/colors_mixer.asp?colorbottom=000000&colortop=FFFFFF)
* For Date and Time function: [Date and Time JS](https://javascript.info/date#setting-date-components)
* For Neomorphism: [Writing CSS for Neomorphism](https://www.youtube.com/watch?v=Gv0dy51SYL0)
* Help for Neomorphism: [Neomorphism](https://neumorphism.io/)
* More about Neomorphism: [CSS-tricks](https://css-tricks.com/neumorphism-and-css/)

## ⚙️ How It Works

- JavaScript retrieves the current system time using the `Date` object  
- The hours, minutes, and seconds are converted into rotation angles  
- CSS `transform: rotate()` is used to rotate the clock hands  
- The clock updates every second to maintain real-time accuracy  

---

## 📁 Project Structure

```text
AnalogClock/
│
├── index.html    # Main HTML file
├── style.css     # Clock styling and layout
├── script.js     # Time logic and hand movement
└── README.md     # Project documentation