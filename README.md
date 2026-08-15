# Mohammad Reza (Arya) Gerami — Personal Website & Technical Hub

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrezagerami.github.io)
[![YouTube Channel](https://img.shields.io/badge/YouTube-Post--QuantumEdge-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@Post-QuantumEdge)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohammad%20Reza%20Gerami-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mohammad-reza-gerami/)

Welcome to the official source repository for the personal website and technical portfolio of **Mohammad Reza (Arya) Gerami** — PhD Researcher in Post-Quantum Cryptography & Cybersecurity, Founder of QuantumGuard Bridge, and Security Consultant.

🌐 **Live Website**: [https://mrezagerami.github.io](https://mrezagerami.github.io)

---

## 🔬 About the Author

Mohammad Reza (Arya) Gerami is a PhD candidate in Computer Engineering at **Polytechnique Montréal** (LARIM & LINCS Labs). His research focuses on designing **hybrid post-quantum cryptographic (PQC) protocols** combining classical and NIST-standardized primitives (ML-KEM, ML-DSA, SLH-DSA) to secure resource-constrained drone (UAV) and IoT networks. 

Prior to his PhD, he accumulated 15 years of industry experience across cloud security architecture, network engineering, SIEM logging (ELK / Splunk), and high-performance computing (HPC) clusters. He is also the founder of **QuantumGuard Bridge (QGB)**, a cybersecurity startup awarded 1st place in the Polytechnique Montréal Cybersecurity Innovation Competition (2025).

---

## ✨ Features of the Website

- **Modern Cyber Aesthetic**: Engineered with glassmorphism, responsive HSL dark mode, glowing accents, and smooth micro-animations.
- **Interactive Portfolio Sliders**: Custom-built hero and expertise sliders highlighting research areas, consulting services, and technical background.
- **Dedicated YouTube Video Blog (`blog.html`)**:
  - Live video hub featuring technical posts from the official YouTube channel **[@Post-QuantumEdge](https://www.youtube.com/@Post-QuantumEdge)**.
  - **In-Place 16:9 HD Streaming**: Responsive embedded YouTube players allow visitors to stream videos directly on the site, driving real view counts.
  - **Direct Engagement CTAs**: **Watch on YouTube** and **Subscribe** buttons (`?sub_confirmation=1`) beneath every video post.
  - **Live Search & Tag Filters**: Instant client-side filtering by categories (*PQC Algorithms, NIST Standards, Quantum Readiness, AI Security*) and keywords.
  - **One-Click Link Sharing**: Clipboard copy integration with visual toast notifications.
- **Startup Showcase**: Dedicated section detailing QuantumGuard Bridge (QGB) platform capabilities and Cryptographic Bill of Materials (CBOM) generation.
- **Mobile Responsive & Accessible**: Fluid typography using Google Fonts (`Inter`) and CSS grid/flexbox layouts.

---

## 🛠️ Tech Stack & Architecture

- **Frontend**: Standard HTML5, Modular Vanilla JavaScript (ES6+)
- **Styling**: Modern CSS3 (CSS Variables, Flexbox, Grid, Glassmorphism backdrop filters)
- **Typography & Icons**: Google Fonts (`Inter`), Inline SVG Icons
- **Media Integration**: YouTube Iframe Player API & Direct Channel Subscription Protocol
- **Hosting**: GitHub Pages (`main` branch root deployment)

---

## 📁 Repository Structure

```text
mrezagerami.github.io/
├── index.html              # Main homepage (Hero, About, Expertise, Research, QGB Startup, Video Teaser, Contact)
├── blog.html               # Video Blog & Technical Hub (Search, Category Filters, Embedded YouTube Players, CTAs)
├── cv/
│   └── mr.gerami-cv.pdf    # Downloadable Curriculum Vitae
├── images/                 # Portfolio graphics, diagram assets, profile images
└── README.md               # Repository documentation
```

---

## 💻 Local Development & Preview

Because the site is built with vanilla web standards, no complex build tools or `npm install` steps are required.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mrezagerami/mrezagerami.github.io.git
   cd mrezagerami.github.io
   ```

2. **Serve locally**:
   - Open `index.html` directly in your web browser, OR
   - Run a lightweight local HTTP server:
     ```bash
     # Using Python
     python -m http.server 8000
     ```
   - Navigate to `http://localhost:8000` in your browser.

---

## 📹 Adding New YouTube Video Posts

To publish a new video post on the blog page, open `blog.html` and append a new object to the `postsData` array:

```javascript
{
  id: 'unique-video-slug',
  title: "Your Video Title Here",
  category: "Post-Quantum Cryptography", // 'Network Security' | 'Post-Quantum Cryptography' | 'NIST Standards' | 'Quantum Readiness' | 'AI Security'
  date: "2026-04-01",
  duration: "15 min watch",
  embedUrl: "https://www.youtube.com/embed/YOUR_YOUTUBE_VIDEO_ID",
  videoUrl: "https://www.youtube.com/watch?v=YOUR_YOUTUBE_VIDEO_ID",
  excerpt: "Short 2-3 sentence overview of what security engineers will learn from this video tutorial.",
  tags: ["Tag1", "Tag2", "Tag3"]
}
```

---

## 📬 Contact & Social Links

- **Website**: [mrezagerami.github.io](https://mrezagerami.github.io)
- **YouTube Channel**: [@Post-QuantumEdge](https://www.youtube.com/@Post-QuantumEdge)
- **LinkedIn**: [mohammad-reza-gerami](https://www.linkedin.com/in/mohammad-reza-gerami/)
- **GitHub**: [@mrezagerami](https://github.com/mrezagerami)
- **Startup**: [QuantumGuard Bridge](https://quantumguardbridge.com/)
- **Book a Call**: [Calendly 30-Min Consultation](https://calendly.com/mr-gerami/30-minute-meeting)
- **Email**: [mr.gerami@gmail.com](mailto:mr.gerami@gmail.com)

---

&copy; 2026 Mohammad Reza Gerami. All rights reserved.
