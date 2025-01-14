# Transport Logistics Website

## Overview
The Transport Logistics Website is a modern web application designed to streamline and enhance logistics and transport services. The website incorporates interactive features and responsive design to provide an excellent user experience. This project demonstrates the integration of animations, navigation indicators, and a clean UI layout.

## Features
- **Responsive Design**: Optimized for mobile and desktop devices.
- **Navigation Indicator**: Highlights active sections as the user scrolls.
- **Page Swipes**: Smooth transitions between pages.
- **Animations on Scroll**: Adds interactivity and visual appeal.
- **Order Tracking**: Users can track their orders through a dedicated page.
- **Static Pages**: Includes single post and other informational pages.

## File Structure
### Main Project Structure
```plaintext
Transport_logistics_website/
├── .vscode/
├── assets/
│   ├── css/
│   │   └── main.css
│   ├── images/
│   └── js/
│       ├── animation_on_scroll.js
│       ├── nav_indicator_onscroll.js
│       ├── page_slides.js
│       ├── page_swiper.js
├── .DS_Store
├── .gitignore
├── index.html
├── input.css
├── package-lock.json
├── package.json
├── procedure.text
├── single_post.html
├── tailwind.config.js
├── track_order.html
```

### Description of Key Files
- **`index.html`**: Main landing page for the website.
- **`assets/css/main.css`**: Contains styles for the website.
- **`assets/js/`**: Folder housing JavaScript files for interactive features such as animations and navigation.
  - `animation_on_scroll.js`: Implements animations triggered by scrolling.
  - `nav_indicator_onscroll.js`: Highlights navigation links based on the user's scroll position.
  - `page_slides.js`: Manages page sliding effects.
  - `page_swiper.js`: Adds swipe functionality for enhanced navigation.
- **`tailwind.config.js`**: Configuration file for Tailwind CSS.
- **`track_order.html`**: A page dedicated to tracking logistics orders.

## Setup Instructions
### Prerequisites
- Node.js installed on your system.
- A code editor like VS Code.

### Steps to Run Locally
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Afoudo-Richard/Transport_logistics_website
   cd Transport_logistics_website
   ```
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Start Development Server**:
   ```bash
   npm run start
   ```
4. Open the project in your browser at `http://localhost:3000` (or the specified port).

## Technologies Used
- **HTML5**
- **CSS3** (Tailwind CSS for styling)
- **JavaScript**
- **Node.js** (for package management and dependencies)

## Contribution Guidelines
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
Thank you for checking out this project! Contributions and suggestions are highly appreciated.
