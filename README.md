<p>This project demonstrates a simple ON/OFF functionality for a bulb using JavaScript. When the button is clicked, it toggles the bulb image between ON and OFF states.</p>


<b>Introduction</b>
<br>
<p>The Bulb ON/OFF project is a straightforward example of how to manipulate the DOM using JavaScript. It helps understand event handling and updating the UI based on user interactions. The bulb starts in the ON state and changes to OFF when clicked, and vice versa.</p>

<br>
<b>Prerequisites</b>
<br>
<p>To run this project, you will need:</p>
<br>
<p>A web browser (Chrome, Firefox, Safari, etc.)
Basic knowledge of HTML and JavaScript</p>
<br>

<b>📌Installation</b>
<br>
1)Clone the repository or download the zip file using bash command
<br>
🔗<p>git clone https://github.com/yourusername/bulb-on-off.git</p>
<br>
2)Navigate to the project directory.
<br>
<p>📍bash</p>
 👇cd bulb-on-off
 <p>Ensure you have the bulb images (bulb-on.png and bulb-off.png) in the same directory as your HTML file.</p>
 
<br>

<b>Usage</b>
<p>Open the index.html file in your web browser.

You will see a bulb image and two buttons labeled "Light ON" and "Light OFF".

Click the "Light ON" button to turn the bulb on and the "Light OFF" button to turn the bulb off.</p>
<br>
<b>Code Overview</b>
<br>
<b>HTML</b>
The HTML file includes the structure of the webpage, the image element for the bulb, and the buttons to control the bulb state.
<br>
<b>html</b>
<br>
<p>
<!DOCTYPE html>
<html lang="en">
<head>
<body>
   <h1>BULB On/Off</h1>
   <p>Clicking on Light ON button turn On the bulb and vice-versa</p>
   <center>
   <img id="bulb" src="bulb-on.png" width="100px" height="180px">
   <p>
      <button type="button" onclick="light(1)">Light ON</button>
      <button type="button" onclick="light(0)">Light OFF</button>
   </p>
   </center>
</body>
</head> 
</html>
</p>

<br>
<b>JavaScript</b>
<br>
The JavaScript code is embedded within the HTML file. It defines the function to change the bulb image source based on the button clicked.
<br>
<b>Contributing</b>
<br>
 <p>Contributions are welcome! If you have suggestions for improvements or want to report a bug, please open an issue or submit a pull request.</p>
<br>
 <p>Feel free to modify this README to suit your project's specific details and needs.</p>

https://github.com/pushpakumari98/HTML-CSS-JS-Project/assets/153999245/528d24dd-d7fc-42d0-b429-35e47f709c77



