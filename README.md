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

The website’s information is organized in a single-page layout that follows a clear and hierarchical structure, allowing users to easily locate the most relevant information at a glance. The content is divided into two main areas: a sidebar containing personal and contact information, and a main section that focuses on my background, work experience, and education. This structure provides a simple and intuitive browsing experience, making it ideal for recruiters or employers who want to evaluate my profile quickly and efficiently.

The **sidebar** includes my **name**, **profile photo**, and **professional title**, immediately identifying the purpose of the website. Below that, the **contact section** lists essential information such as email, phone number, and location, allowing potential employers to contact me directly. The sidebar also features my **skills** and **languages**, displayed through progress bars that visually represent my level of proficiency in each area. This combination of text and visual elements helps communicate key information in a clear and engaging way.

The **main content area** expands on the professional side of my profile. It begins with an **About Me** section that provides a short description of who I am, my interests, and my general approach to work. Following that, the **Work Experience** section lists the companies where I have worked, the positions I held, the corresponding years, and a few bullet points describing my main functions or responsibilities within each role. Finally, the **Education** section summarizes my academic background, including degrees and institutions, to give a complete overview of my qualifications.

The structure follows a **top-down, user-centered logic**, ensuring that visitors first see who I am and how to contact me, and then learn about my skills, experience, and education. The information is visually separated with consistent spacing and headings, and the layout adapts responsively to any screen size for a smooth and accessible user experience.

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

The design emphasizes clarity, balance, and hierarchy, ensuring recruiters can quickly find the most relevant information. Every visual element has been carefully chosen to guide the reader’s attention naturally from one section to another, creating a smooth and coherent reading flow. The consistent use of spacing, typography, and color not only reinforces the visual identity of the page but also improves legibility, helping users focus on content rather than decoration. This results in a professional, organized, and trustworthy presentation that reflects both technical precision and aesthetic awareness.


---

### Figma Project

[Link to the Figma project](https://www.figma.com/design/hcKDv3xtjftMdwypOGQdhf/CV?t=eyJTvpdmXO2EOjEW-1)

---

### Website Code

The repository includes at least the following files:

- `index.html`
- `CV.css`

All files are structured to ensure readability, maintainability, and semantic HTML markup.

---

### Author

**Name:** Fran José Álvarez Pascual
