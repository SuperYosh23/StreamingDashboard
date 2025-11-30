
<img width="952" height="99" alt="Untitled drawing" src="https://github.com/user-attachments/assets/5ac8cf17-c221-41c8-9e0a-213e86dc32ec" />

A polished, responsive HTML/CSS/JS dashboard showcasing streaming service tiles with glassmorphism styling, animated background gradients, and a small options menu for runtime customization.

This was originaly used on my Dell Optiplex 3010 running Windows 11 and a GameCube WaveBird Controller mapped as:

A:Click

B:Browser Back

Left Stick:Move Mouse

Right Stick:Scroll

L/R:Track Forward/Back

Z:Play/Pause

X/Y:Play/Pause

Start:Open On-Screen Keyboard

### Features

*   **Glassmorphism tiles** with brand glow and staggered entrance animations.
    
*   **Animated background gradients** with a selection of presets and runtime switching.
    
*   **Options menu** to toggle performance mode and change background gradient.
    
*   **Lightweight vanilla JavaScript** with persistent settings via localStorage.
    
*   **Accessible controls** using semantic elements and ARIA attributes.
    

### Getting Started
    
#### Run the web hosted version

1.  Go to [https://superyosh23.github.io/StreamingDashboard/](https://superyosh23.github.io/StreamingDashboard/)
    

#### Run locally

1.  Clone or copy the project folder.
    
2.  Open index.html in any modern browser.
    

### Behavior and Persistence

*   **Options menu** toggles visibility without removing it from the DOM. It uses aria-hidden for accessibility.
    
*   **Performance mode** toggles the performance class on to disable hover transforms and glows.
    
*   **Persistence**: selected gradient and performance mode are saved to localStorage under keys gradient and performance. The script reads these on DOMContentLoaded.
    

### Credits

*   Built with plain HTML, CSS, and JavaScript.
    
*   Icons and logos in the demo are loaded from public image URLs, I do not own them.
    
*   Like most of my projects, this is almost entirely AI genarated.
