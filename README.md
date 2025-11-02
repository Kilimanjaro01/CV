# Creative Portfolio Website

## Project Analysis

### User Profile (User Persona)

This website is intended for a company or recruiter who might be interested in hiring me.  
It has been designed as a professional online version of my CV, allowing employers to quickly understand who I am, what skills I have, and what kind of work I can do.  

The target audience includes hiring managers, HR professionals, or potential clients looking for someone with my technical and creative background.  
The structure and content of the site aim to make their experience as efficient and pleasant as possible — everything is clearly organized, easy to read, and accessible from any device.  

My goal is to make a **strong first impression** by presenting myself as a competent, reliable, and detail-oriented professional.  
Through this website, I want to communicate not only my experience and education, but also my sense of design, organization, and commitment to quality work.

---

### Information Architecture

The website’s information is organized into four main sections to ensure clear and intuitive navigation. The **Home page** introduces the designer and the purpose of the site, creating a strong first impression. The **Portfolio section** showcases selected projects with images and short descriptions that help visitors quickly understand each project’s context. The **About page** provides background information about the designer’s education, skills, and approach to design. The **Contact page** includes a simple form and social media links, allowing potential employers or collaborators to get in touch easily.

This structure follows a linear and user-centered logic. Visitors can reach any part of the site in one or two clicks, promoting accessibility and engagement. The consistent navigation bar and footer help maintain orientation throughout the browsing experience.

---

### Visual Design

The visual design follows a **modern and minimalistic** aesthetic, using a **two-column layout** with a dark sidebar and a light content area to create visual contrast.  

Key design decisions include:

- **Color Palette:**  
  - Dark navy (`#1e2a38`) for the sidebar background to convey professionalism and contrast with white text.  
  - Accent blue (`#4fc3f7`) used for highlights and section dividers, bringing energy and coherence.  
  - Light grey (`#f4f6f8`) as the main background color for readability and visual balance.  
- **Typography:**  
  - A clean sans-serif font (`"Segoe UI", Roboto, Helvetica, Arial`) for clarity and modernity.  
- **Layout and Spacing:**  
  - Generous padding and spacing between sections to enhance readability.  
  - Rounded profile photo and subtle section dividers to maintain a friendly but professional appearance.  
- **Responsiveness:**  
  - The layout adapts to tablets and mobile devices by stacking the sidebar on top.  
  - All text remains legible across devices thanks to relative font sizes and flexible containers.
  
The layout automatically adapts to different screen widths using a **CSS media query**:

```css
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
  .sidebar {
    width: 100%;
    text-align: center;
  }
}
```

The design emphasizes **clarity, balance, and hierarchy**, ensuring recruiters can quickly find the most relevant information.

---

### Figma Project

[Link to the Figma project](https://www.figma.com/your-project-link)

---

### Website Code

The repository includes at least the following files:

- `CV.html`
- `CV.css`

All files are structured to ensure readability, maintainability, and semantic HTML markup.

---

### Public Website

[View the website on GitHub Pages](https://yourusername.github.io/your-project/)

---

### Author

**Name:** Fran José Álvarez Pascual
