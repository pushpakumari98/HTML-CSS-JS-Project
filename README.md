<p>This project demonstrates a simple ON/OFF functionality for a bulb using JavaScript. When the button is clicked, it toggles the bulb image between ON and OFF states.</p>


<b>Introduction</b>
<br>
The Bulb ON/OFF project is a straightforward example of how to manipulate the DOM using JavaScript. It helps understand event handling and updating the UI based on user interactions. The bulb starts in the ON state and changes to OFF when clicked, and vice versa.

<br>
👇Prerequisites
To run this project, you will need:

A web browser (Chrome, Firefox, Safari, etc.)
Basic knowledge of HTML and JavaScript
<br>

📌Installation
1)Clone the repository or download the zip file.

🔗bash 
<link rel="git clone https://github.com/yourusername/bulb-on-off.git">

2)Navigate to the project directory.

📍bash
 📌cd bulb-on-off
 <p>Ensure you have the bulb images (bulb-on.png and bulb-off.png) in the same directory as your HTML file.</p>
 
<br>

<b>Usage</b>
Open the index.html file in your web browser.

You will see a bulb image and two buttons labeled "Light ON" and "Light OFF".

Click the "Light ON" button to turn the bulb on and the "Light OFF" button to turn the bulb off.
<br>

<b>Code Overview</b/>
HTML
The HTML file includes the structure of the webpage, the image element for the bulb, and the buttons to control the bulb state.
<br>
<b>html</b>

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Bulb ON/OFF </title>
    <script type="text/javascript">
        function light(show){
            var pic;
            if(show==0){
                pic="bulb-off.png";
            }
            else{
                pic="bulb-on.png";
            }
            document.getElementById('bulb').src=pic;
        }
    </script>
</head> 
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
</html>
<br>
<b>JavaScript</b>
The JavaScript code is embedded within the HTML file. It defines the function to change the bulb image source based on the button clicked.

javascript

function light(show){
    var pic;
    if(show==0){
        pic="bulb-off.png";
    }
    else{
        pic="bulb-on.png";
    }
    document.getElementById('bulb').src=pic;
}
<br>
<b>Contributing</b>
 Contributions are welcome! If you have suggestions for improvements or want to report a bug, please open an issue or submit a pull request.

<br>
 Feel free to modify this README to suit your project's specific details and needs.
