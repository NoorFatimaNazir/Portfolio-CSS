# Personal Profile Website — CSS Project

A four-page personal profile website (Home, About Me, Contact Me, Hobbies) built with
semantic HTML and styled entirely with CSS to be modern, attractive, and fully responsive
using a **mobile-first** approach.

## 🔗 Live Demo

<!-- TODO: paste your Vercel URL here after deploying -->
[View Live Site](https://your-project.vercel.app)

## 📄 Pages

| Page | File | Description |
|------|------|-------------|
| Home | `home.html` | Hero header, profile photo, skills grid, and article cards |
| About Me | `about.html` | Personal bio inside a styled box-model container |
| Contact Me | `contact.html` | Styled contact form with labels, inputs, and a submit button |
| Hobbies | `hobbies.html` | Hobbies list with custom bullets in a Flexbox layout |

All four pages share a single external stylesheet, `style.css`, for consistent styling.

## 🎨 CSS Concepts Demonstrated

This project demonstrates the following concepts (each is marked with a comment in
`style.css` where it appears):

- ✅ CSS Syntax
- ✅ Inline CSS *(one example — the availability note on Home)*
- ✅ Internal CSS *(one example — `<style>` block in `home.html`)*
- ✅ External CSS *(main stylesheet, `style.css`)*
- ✅ Element, Class, ID, and Group selectors
- ✅ Cascading (documented with an example in the CSS comments)
- ✅ Typography — font family, size, weight, color, alignment
- ✅ Colors and backgrounds
- ✅ Box Model — margin, padding, border, box-sizing
- ✅ Display properties — block, inline, inline-block
- ✅ Positioning — relative, absolute, and sticky
- ✅ Flexbox layouts (nav, skills, articles, hobbies)
- ✅ Transitions
- ✅ CSS Animations (`@keyframes`)
- ✅ Responsive design with mobile-first media queries

**Optional extras included:** smooth scrolling, card design, box shadows, and a custom
color theme.

## 📁 Project Structure

\`\`\`
project-root/
├── home.html
├── about.html
├── contact.html
├── hobbies.html
├── style.css
└── README.md
\`\`\`

## 🚀 Running Locally

No build tools or dependencies are required — this is a static HTML/CSS site.

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
   cd YOUR-REPO
   \`\`\`
2. Open `home.html` directly in your browser, or use a live server
   (e.g. the VS Code "Live Server" extension) for auto-reload while editing.

## 🌐 Deployment

This project is deployed with [Vercel](https://vercel.com):

1. Push the project to a public GitHub repository.
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
3. Click **Add New Project**, import the repository, and set the Framework Preset to
   **Other**.
4. Click **Deploy** — Vercel will host the site and give you a live `.vercel.app` link.
5. Every future `git push` automatically redeploys the site.

## 📱 Responsive Design

The stylesheet is written **mobile-first**: base styles target small screens, and
`@media (min-width: ...)` breakpoints progressively enhance the layout for tablets
(768px) and desktops (1024px).

## ✍️ Author

<!-- TODO: your name, GitHub profile link, email/contact -->
**Noor Fatima**
[GitHub](https://github.com/NoorFatimaNazir) · [Email](mailto:noornazir179@gmail.com)

## 📜 License

This project was created for educational purposes as part of the iCodeGuru
Zero to Gen AI Developer Bootcamp.
