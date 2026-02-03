# 🖼️ Horizon Gallery | Live API & Infinite Scroll Portfolio - Task 12

**A professional, high-performance image discovery engine powered by the Pexels API, featuring infinite scroll, real-time search, and a glassmorphic UI.**

### 🔴 **Live Demo:** [Click Here to View](https://sharanx77.github.io/task_12.elevateslabs/)

---

## 🚀 About The Project

**"Horizon Gallery"** was developed for the **Elevate Labs Web Development Internship (Task 12)**. What began as a static layout has evolved into a dynamic **Single Page Application (SPA)** that interacts with external cloud databases. This project demonstrates advanced JavaScript concepts, including asynchronous programming (fetch API), intersection observers for high-performance UI, and complex state management.



### 🎯 Key Features
* **Live API Integration:** Dynamically fetches high-resolution imagery from the **Pexels API** based on user queries.
* **Infinite Scroll Engine:** Implements the **Intersection Observer API** to detect the bottom of the page and automatically load more content for a seamless "endless" experience.
* **Real-Time Search:** A custom filtering system that allows users to explore specific themes (e.g., "Cyberpunk", "Nature", "Architecture") instantly without reloading the page.
* **Custom Modal System:** A handcrafted JavaScript lightbox that handles high-res image previews, background scroll-locking, and keyboard accessibility.
* **Glassmorphic UI:** A modern aesthetic utilizing `backdrop-filter: blur`, CSS Grid, and fluid animations to provide a premium user experience.

---

## 🧰 Tech Stack

* **HTML5 & CSS3:** Semantic markup and advanced styling (Flexbox/Grid, Glassmorphism).
* **JavaScript (ES6+):** * **Asynchronous JS:** `async/await` and `fetch` for API communication.
    * **Intersection Observer API:** For high-performance infinite scrolling.
    * **DOM Manipulation:** Dynamic rendering of API-sourced content.
* **Pexels API:** The engine providing professional photography data.
* **Development Tools:** VS Code, Git, and GitHub Pages for deployment.

---

## 📂 Project Structure

/Task_12_Image_Gallery
├── index.html      # Main Structure & Modal Markup
├── style.css       # Layout, Glassmorphism, & Animation Definitions
└── script.js       # API Integration, Infinite Scroll, & Modal Logic

---

## 🛠️ Technical Implementation Details
This project fulfills and exceeds all requirements for Task 12:

* **API Management:** Securely handling headers and authorization for external requests.
* **Intersection Observer:** Optimized the "Loading Sentinel" to trigger data fetches only when needed, reducing unnecessary API calls.
* **Dynamic Content Swap:** Used JS to swap the `src` and photographer metadata in the modal instantly.
* **Accessibility & UX:** Implemented "ESC" key support to exit modals and locked the body scroll to maintain user focus.

---

## 🔮 Future Roadmap
* ✅ **Phase 1:** (Completed) Infinite Scroll & API Integration.
* 🔄 **Phase 2:** Implement **Local Storage** to allow users to "Favorite" images.
* 🔄 **Phase 3:** Add a **Download Engine** to save high-res versions directly from the modal.
* 🔄 **Phase 4:** Transition to **React.js** for more scalable component management.

---

## 👨‍💻 Author
**B Sharana Basava** *Electronics and Communication Engineering Student*

* **LinkedIn:** [B Sharana Basava](https://www.linkedin.com/in/b-sharanabasava/)
* **GitHub:** [Sharanx77](https://github.com/Sharanx77)
* **Email:** [b.sharanabasava2006@gmail.com](mailto:b.sharanabasava2006@gmail.com)

---

## 🙌 Acknowledgments
* **Elevate Labs** for the structured learning path and challenges.
* **Pexels** for providing the high-quality professional photography API.
* **Gemini AI** for code optimization, architectural guidance, and UX assistance.
