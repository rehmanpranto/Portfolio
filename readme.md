# Portfolio Website - Mohammad Mahibur Rahman

This is the repository for my personal portfolio website, showcasing my skills, projects, and experience as a Data Analyst and MIS enthusiast.

## Live Demo

**(Link to your deployed portfolio website - e.g., `https://yourusername.github.io/portfolio/` or your custom domain)**

## Overview

This portfolio is a single-page application built with modern web technologies to provide a clean, responsive, and engaging user experience. It features:

* **Responsive Design:** Adapts to various screen sizes (desktop, tablet, mobile).
* **Dark/Light Mode:** User-selectable theme preference with system preference detection.
* **Interactive UI Elements:** Smooth animations and transitions for a dynamic feel.
* **Clear Sections:** Dedicated areas for Home, About Me, Skills, Projects & Experience, and Contact information.

## Technologies Used

* **HTML5:** For the basic structure and content of the website.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development and responsive design.
* **JavaScript (Vanilla JS):** For interactive features like the mobile menu and dark mode toggle.
* **Font Awesome:** For scalable vector icons.
* **Google Fonts (Inter):** For clean and modern typography.

## Project Structure
.
├── index.html         # Main HTML file
├── profile.jpg        # (Placeholder for your profile picture)
└── README.md          # This file
## Key Features Implemented

* **Hero Section:** Engaging introduction with an animated title and call to action.
* **About Me:** Detailed personal introduction with a profile picture.
* **Skills Section:**
    * Categorized skills with relevant icons.
    * Visually distinct "skill pills" for easy scanning.
* **Projects & Experience Section:**
    * Presented in a visually appealing timeline format.
    * Details past roles and ongoing academic projects.
* **Contact Section:** Clear call to action with email and links to social profiles (LinkedIn, GitHub).
* **Responsive Navigation:**
    * Sticky header for easy navigation.
    * Hamburger menu for mobile devices.
* **Dark Mode Toggle:**
    * Allows users to switch between light and dark themes.
    * Remembers user preference via `localStorage`.
    * Detects system's preferred color scheme on initial load if no preference is set.
* **Smooth Scrolling:** For navigation links within the page.
* **Footer:** Displays copyright information and the current year dynamically.

## Setup and Usage

1.  **Clone the repository (optional, if you're hosting it yourself):**
    ```bash
    git clone [https://github.com/yourusername/your-portfolio-repo.git](https://github.com/yourusername/your-portfolio-repo.git)
    cd your-portfolio-repo
    ```
2.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser to view the website locally.
3.  **Replace Placeholder Image:**
    * Locate the `<img>` tag within the "About Me" section in `index.html` (around line 217).
    * Change the `src` attribute from `https://placehold.co/400x400/6366F1/FFFFFF?text=MMR&font=inter` to the path of your actual profile picture (e.g., `profile.jpg` if it's in the same directory, or `images/profile.jpg` if it's in an `images` subfolder).

## Customization

* **Content:** Edit the text content directly in `index.html` within the respective sections (About Me, Skills, Projects, Contact details).
* **Styling (Colors, Fonts):**
    * Primary color variables (e.g., `--accent-primary`, `--bg-primary`) are defined in the `<style>` section within the `<head>` of `index.html`. You can modify these CSS custom properties to change the theme.
    * Tailwind CSS classes are used extensively for styling. Refer to the [Tailwind CSS Documentation](https://tailwindcss.com/docs) for more information on available utility classes.
* **Profile Picture:** As mentioned in the Setup section, update the image source.
* **Links:** Update social media links in the Contact section and any project links.

## Deployment

You can deploy this website using various hosting platforms:

* **GitHub Pages:** A popular free option for hosting static websites directly from a GitHub repository.
* **Netlify:** Offers a simple drag-and-drop interface or Git-based deployment.
* **Vercel:** Another excellent platform for deploying front-end projects.
* **Traditional Web Hosting:** Upload the files to any web server that supports HTML, CSS, and JS.

## Contributing

While this is a personal portfolio, suggestions for improvements are welcome! Feel free to open an issue or submit a pull request if you have ideas.

## License

This project is open source and available under the [MIT License](LICENSE.md) (You would need to create a LICENSE.md file if you want to specify one, typically choosing a permissive license like MIT for personal portfolios).

---

Thank you for checking out my portfolio project!

**Mohammad Mahibur Rahman**
* [LinkedIn](https://www.linkedin.com/in/rahmanpranto)
* [GitHub](https://github.com/rehmanpranto)
* Email: `rehmanpranto@gmail.com`
