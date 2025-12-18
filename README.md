
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
![1](https://github.com/AviralJaiswal/Virtual-Analog-clock/blob/main/images/1.jpg)
![2](https://github.com/AviralJaiswal/Virtual-Analog-clock/blob/main/images/2.jpg)
![3](https://github.com/AviralJaiswal/Virtual-Analog-clock/blob/main/images/3.jpg)

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