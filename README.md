# ⚡️ AlgoVisor - Engineering Grade Analyzer


<img width="2936" height="1672" alt="image" src="https://github.com/user-attachments/assets/032599e3-cc0f-4b5b-8317-bc80dee481a3" />


**Understand your code's true performance instantly.** AlgoVisor is a powerful, client-side web application built for students and developers. Simply paste your algorithm, connect your Gemini API key securely, and instantly calculate precise Big-O metrics along with interactive execution graphs.
🔔**How to get api? :**  
🌐 **Live Demo:** [https://algovisor.netlify.app/](https://algovisor.netlify.app/)

---

## ✨ Key Features
* 🚀 **Instant Execution:** Powered by Google's `gemini-2.5-flash` model, returning highly accurate Time and Space complexity (Big-O) analysis in milliseconds.
* 📈 **Visual Mapping:** Automatically plots your algorithm's growth rate against standard mathematical curves (O(1), O(log n), O(n), O(n log n), O(n²), O(2ⁿ)) using **Chart.js**.
* 🌍 **Language Agnostic:** Drop in C++, Java, Rust, Python, or JavaScript. The AI evaluates the underlying logical structures, not just the syntax.
* 🔒 **100% Client-Side & Secure:** No backend required! Your Google Gemini API key is stored safely in your browser's local storage and is *never* sent to our servers.
* 🎨 **Modern UI/UX:** A sleek, dark-themed interface built with Tailwind CSS, featuring smooth animations and a responsive design.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, Vanilla JavaScript, CSS3
* **Styling:** Tailwind CSS (via CDN)
* **Icons:** Lucide Icons
* **Data Visualization:** Chart.js
* **AI Integration:** Google Generative AI SDK (`@google/generative-ai`)

---

## 🚀 Getting Started

Since AlgoVisor is a fully client-side application, getting it running locally is incredibly simple.

### Prerequisites
You will need a **Google Gemini API Key**. You can get one for free from Google AI Studio.

### Installation & Usage

1. **Clone the repository:** `git clone https://github.com/nowordsyours/algovisor.git`
2. **Navigate to the directory:** `cd algovisor`
3. **Run the app:** Simply open the `index.html` file in your favorite modern web browser. (Optional: Use an extension like Live Server in VS Code for a better development experience).
4. **Connect API:** Click the "API Key" 🔑 button in the top navigation bar, paste your Google Gemini API Key, and click Connect.
5. **Analyze:** Paste your code snippet into the editor and click "Compute Complexity".

---

## 🧠 Under the Hood
AlgoVisor utilizes the `@google/generative-ai` library to communicate directly from your browser to the Gemini 2.5 Flash model. It uses strict prompt engineering to force the AI to return a cleanly formatted JSON object containing the exact Big-O notations and graph types. Once received, the app updates the DOM and triggers a Chart.js re-render to highlight the specific growth curve of your algorithm.

---

## 👨‍💻 Developed By
**Amit Singh Bisht** | Web Developer | C++ & DSA Enthusiast

*"Consistency is the only algorithm that matters."*

* 🔗 **LinkedIn:** [Amit Singh Bisht](https://www.linkedin.com/in/amit-singh-bisht-742b1b302/)
* 🐙 **GitHub:** [@nowordsyours](https://github.com/nowordsyours)
* 💻 **LeetCode:** [amitsinghbisht](https://leetcode.com/u/amitsinghbisht/)

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---

## 📜 License
This project is open-source and available under the MIT License.
