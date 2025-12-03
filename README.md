# Dr. Mehnaj Khatoon - Professional Portfolio

![Portfolio Preview](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)

Welcome to the official portfolio repository of **Dr. Mehnaj Khatoon**, a dedicated Researcher and Bioinformatics Expert. This portfolio showcases her academic background, research experience, publications, and professional achievements.

## 🌟 Features

-   **Modern & Responsive Design**: Built with a mobile-first approach ensuring great experience on all devices.
-   **Dark/Light Mode**: Includes a built-in theme toggle to switch between light and dark modes for better accessibility and user preference.
-   **Clean UI/UX**: Utilizes a clean, professional layout with smooth animations and transitions.
-   **Interactive Elements**: sticky navigation, hover effects, and smooth scrolling.

## 🛠️ Technologies Used

-   **HTML5**: Semantic markup for structure.
-   **Tailwind CSS**: Utility-first CSS framework for rapid and responsive styling (loaded via CDN).
-   **JavaScript**: Vanilla JS for handling theme toggling and mobile menu interactions.
-   **FontAwesome**: For vector icons.
-   **Google Fonts**: 'Inter' font family for modern typography.

## 🚀 Getting Started

Since this project uses Tailwind CSS via CDN, you don't need to install any complex dependencies.

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```
2.  **Open the file:**
    Simply open `index.html` in your preferred web browser.

## 📂 Project Structure

```
├── index.html      # Main HTML file containing the portfolio structure and logic
├── README.md       # Project documentation
└── resource/       # Directory for static assets (images, etc.)
```

## 🎨 Customization

### Editing Content
You can easily update the content by editing the `index.html` file. Look for the relevant sections (About, Experience, Publications) and modify the text within the HTML tags.

### Changing Colors
The color scheme is defined in the `tailwind.config` script within the `<head>` of `index.html`. You can modify the `primary`, `secondary`, `dark`, and `light` colors to match your preference.

```javascript
tailwind.config = {
    darkMode: 'class',
    theme: {
        extend: {
            colors: {
                primary: '#3B82F6', // Change this hex code
                secondary: '#10B981', // Change this hex code
                // ...
            }
        }
    }
}
```

## 👤 Author

**Dr. Mehnaj Khatoon**
-   Researcher at ICAR-NIVEDI
-   [LinkedIn Profile](https://www.linkedin.com/in/mehnaj-khatoon-741250230)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---
*Designed & Developed by [nksoftpune](https://navnathkamble.netlify.app/)*
