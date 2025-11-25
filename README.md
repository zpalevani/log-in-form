# Modern Responsive Login Form

A clean, aesthetic, and fully responsive login interface built with **HTML5** and **Tailwind CSS**. This project features a split-screen layout, social login options, and a robust Dark Mode toggle that persists user preferences.

https://zpalevani.github.io/log-in-form-tailwind-CDN/ 

## ✨ Features

*   **Responsive Design:** Adapts seamlessly from mobile view (stacked) to desktop view (split-screen).
*   **Dark Mode Support:**
    *   Includes a manual toggle button (Sun/Moon icon).
    *   Detects system preference (OS color scheme).
    *   Persists preference using `localStorage` (remembers your choice on reload).
*   **Modern UI/UX:**
    *   Gradient sidebar.
    *   Floating input labels style.
    *   Google "Sign in" button integration.
*   **Zero Dependencies:** Uses Tailwind CSS via CDN, so no `npm install` or build step is required.

## 🛠️ Technologies Used

*   **HTML5:** Semantic structure.
*   **Tailwind CSS (via CDN):** Utility-first styling for rapid development.
*   **JavaScript:** Vanilla JS for handling dark mode logic and local storage.

## 🚀 How to Run

Since this project uses the Tailwind CDN, you don't need to install Node.js or any build tools.

1.  Clone the repository:
    ```bash
    git clone https://github.com/zpalevani/log-in-form.git
    ```
2.  Navigate to the folder:
    ```bash
    cd log-in-form
    ```
3.  Open `index.html` in any web browser.

## 📂 Project Structure

```text
/log-in-form
├── index.html      # Main structure and Tailwind classes
├── code.js         # (Optional) External JS
├── style.css       # (Optional) Custom styles
└── README.md       # Project documentation
```
🎨 Customization
Changing the Gradient
To change the left panel background, locate this line in index.html:

Html
```<div class="md:w-1/2 bg-gradient-to-br from-blue-600 to-cyan-400 ...">```

Change from-blue-600 and to-cyan-400 to any other Tailwind colors (e.g., from-purple-600 to-pink-500).

Connecting the Form
Currently, the form points to #. To connect it to a backend, update the action attribute in the <form> tag:

Html
```<form action="/your-login-endpoint" method="post">```

📄 License
This project is open source and available for personal or commercial use.
