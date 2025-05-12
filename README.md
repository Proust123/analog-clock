🕰️ My Clock – Analog Clock with JavaScript
A simple, stylish analog clock built using HTML, CSS, and JavaScript. It visually mimics a real clock by rotating hour, minute, and second hands based on the current system time.

🚀 Features
Dynamic analog clock that updates every second.
Styled clock face with hour, minute, and second pins.
Realistic rotation logic using system time.

🛠️ Built With
HTML5 — for structure
CSS3 — for styling and layout
JavaScript — for time-based logic and animation

🧠 How It Works
new Date() fetches the current time.
Rotations:
Hour hand rotates at 30° * hour + (minutes / 2)
Minute hand rotates at 6° * minutes
Second hand rotates at 6° * seconds

A setInterval() ensures the clock updates every second.
