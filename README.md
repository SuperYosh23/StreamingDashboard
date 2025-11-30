### Streaming Dashboard

A polished, responsive HTML/CSS/JS dashboard showcasing streaming service tiles with glassmorphism styling, animated background gradients, and a small options menu for runtime customization.

### Features

*   **Glassmorphism tiles** with brand glow and staggered entrance animations.
    
*   **Animated background gradients** with a selection of presets and runtime switching.
    
*   **Options menu** to toggle performance mode and change background gradient.
    
*   **Lightweight vanilla JavaScript** with persistent settings via localStorage.
    
*   **Accessible controls** using semantic elements and ARIA attributes.
    

### Getting Started

#### Files

*   index.html — main markup, styles, and script (single-file demo).
    
*   Images are loaded via external URLs in the demo; replace with local assets if needed.
    

#### Run the web hosted version

1.  Go to https://superyosh23.github.io/StreamingDashboard/


#### Run locally

1.  Clone or copy the project folder.
    
2.  Open index.html in any modern browser.

   
### Behavior and Persistence

*   **Options menu** toggles visibility without removing it from the DOM. It uses aria-hidden for accessibility.
    
*   **Performance mode** toggles the performance class on to disable hover transforms and glows.
    
*   **Persistence**: selected gradient and performance mode are saved to localStorage under keys gradient and performance. The script reads these on DOMContentLoaded.


### Accessibility and Performance

*   Use descriptive alt attributes for images.
    
*   The options menu uses aria-hidden and is keyboard closable via Escape.
    
*   For low-power devices, enable **Performance mode** to disable hover animations.
    
*   Consider replacing remote images with optimized local assets or SVG sprites to reduce network requests.
    
    

### Credits

*   Built with plain HTML, CSS, and JavaScript.
    
*   Icons and logos in the demo are loaded from public image URLs, I do not own them.

*   Like most of my projects, this is almost entirely AI genarated.
