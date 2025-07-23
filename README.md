# AI-Chatbot-interface-using-html-and-css
I have made 3 versions of this project the second is made with php and the third version is made with laravel

I have compressed the background video so that it can easily be uploaded heere

AI Chat Interface Project

Overview

This project is a responsive AI chat interface built using HTML and CSS, designed to simulate a conversational platform with an AI assistant. It features a fixed right navigation bar with a logo and authentication buttons, a chat container with a message display area, and input controls for sending messages and clearing the chat. The design uses a modern, blurred-background aesthetic with a video background for visual appeal.
Features

Responsive Design: Adapts to various screen sizes using flexible layouts (flex, percentage-based widths) for optimal viewing on desktops, tablets, and mobiles.
Fixed Navigation: Right sidebar (right-nav) with a logo (logo, vid) and buttons for Sign In and Sign Up (right-nav-btns).
Chat Interface: 
Displays user and AI messages (user-message, ai-message) in a scrollable chat box (chat-box) with timestamps (timestamp).
Input area (input-group) with a text input (input-snd) and send button (snd-btn) featuring a Font Awesome icon (fa-angle-right).
Clear chat button (clear-btnn) to reset the conversation.


Visual Design: Uses a blurred background (backdrop-filter: blur), transparent elements with borders, and a video background (bg-video) for a modern look.
Interactive Elements: Hover effects on buttons (snd-btn:hover, clear-btn:hover, btn-outline-secondary:hover) with smooth transitions (transition: background-color .4s ease).

Technologies Used

HTML5: For semantic structure and content.
CSS3: For styling, layout, and visual effects (e.g., backdrop-filter, flex, border-radius, transition).
Font Awesome: For icons (e.g., fa-angle-right) in the send button.
External Resources:
Font Awesome CDN (https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css) for icons.
Video file for background (bg-video source, e.g., vid.mp4).



File Structure

index.html: Main HTML file containing the chat interface and navigation structure.
style.css: CSS file for styling the layout, navigation, chat box, and input controls.
images/: Directory for the logo image (vid class, e.g., logo.png).
videos/: Directory for the background video (bg-video source, e.g., vid.mp4).
Note: Ensure the logo image and video file are placed in their respective folders (images/, videos/) and referenced correctly in index.html.



Naming Conventions
The project uses descriptive class names for clarity:

right-nav: Fixed right navigation sidebar.
logo, vid: Logo container and image/video.
right-nav-btns: Container for Sign In and Sign Up buttons.
chat-container, full-chat: Main chat area and its content.
chat-box: Scrollable message display area.
user-message, ai-message: Individual message types with distinct styling.
input-group, input-snd, snd-btn: Input area, text input, and send button.
clear-box, clear-btnn: Clear chat button container and button.
fa-angle-right: Font Awesome icon for the send button.
timestamp: Message timestamp styling.
bg-video: Background video element.

Setup Instructions

Clone or Download:
Clone the repository or download the project files.


File Placement:
Place index.html and style.css in the project root.
Create an images/ folder and add the logo image (e.g., logo.png for vid class).
Create a videos/ folder and add the background video (e.g., vid.mp4 for bg-video).


Dependencies:
Include Font Awesome CDN in index.html: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">.
Ensure an internet connection to load Font Awesome icons.


Run the Project:
Open index.html in a web browser to view the chat interface.
No server setup is required as it uses static HTML and CSS.



Usage

Navigation: Use the Sign In and Sign Up buttons (right-nav-btns) in the right sidebar to simulate authentication (requires backend integration for functionality).
Chat Interaction:
Enter a message in the text input (input-snd) and click the send button (snd-btn) or press "Enter" to display a user message (requires JavaScript for dynamic functionality).
AI responses are static placeholders (ai-message) and need backend integration for real responses.
Click the Clear Chat button (clear-btnn) to reset the conversation (requires JavaScript for functionality).


Visual Feedback: Hover over buttons (snd-btn, clear-btnn) for background color changes.

Customization

Styling: Modify style.css to change colors, fonts, or layout.
Primary background: transparent with backdrop-filter: blur for glass effect.
Borders: rgb(75, 75, 75) (dark gray).
Text and button color: rgb(160, 160, 160) (light gray).
Hover color: rgb(95, 95, 95) (darker gray for buttons).


Content: Update the logo image, video source, or placeholder text in index.html.
Video Background: Replace the bg-video source in index.html with your own video file (e.g., vid.mp4).
Functionality: Add JavaScript to index.html to enable dynamic chat functionality (e.g., sending messages, fetching AI responses, clearing chat).
Transitions: Adjust hover effects (e.g., transition: background-color .4s ease) for different animations.

Notes

The chat functionality (user-message, ai-message, snd-btn, clear-btnn) is static and requires JavaScript and backend integration (e.g., Node.js, WebSocket, or API) for dynamic messaging.
The background video (bg-video) must be a valid video file (e.g., MP4) placed in the videos/ folder.
Ensure Font Awesome CDN is included in index.html for the send button icon (fa-angle-right) to display correctly.
The project is optimized for modern browsers (Chrome, Firefox, Edge, Safari).
The Sign In and Sign Up buttons are static and require backend integration for authentication.
The chat box (chat-box) supports scrolling (overflow-y: auto) with a custom scrollbar (::-webkit-scrollbar).

Credits

Designed by: Ahmad Samama
Icons: Font Awesome
Images/Video: Placeholder logo and background video (replace with your own).

License
© Copyright 2025 Ahmad Samama. All Rights Reserved.

Chat Interface Image

<img width="1440" height="814" alt="Chat" src="https://github.com/user-attachments/assets/ebe4d613-a574-4146-a211-6f839fb8ad19" />

