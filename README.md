<p align="center">
  <img src="https://raw.githubusercontent.com/Potential17/Potential17/master/user%20(2).gif" width="400" alt="Coding Animation" />
</p>

<p align="center">
  <a href="https://github.com/gaurab72">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=0e75b6&center=true&vCenter=true&width=600&lines=Full+Stack+Developer;BIM+Student+%40+Tribhuvan+University;Open+Source+Enthusiast;Building+Amazing+Web+Apps;React+%7C+Node.js+%7C+MongoDB" alt="Typing Animation" />
  </a>
</p>

<h1 align="center">
  👋 Hi, I'm <span style="color: #0e75b6"><b>Gaurab Hamal</b></span>
</h1>

<p align="center">
  <b>Passionate Web Developer</b> 💻 | BIM Student | Open Source Enthusiast
</p>

<p align="center">
  <a href="https://github.com/gaurab72" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:hamlgaurav80@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/gaurab-hamal" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=gaurab72&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile Views" />
</p>

---

## 🚀 About Me

```javascript
// Let me introduce myself! 👨‍💻
const gaurab = {
  name: "Gaurab Hamal",
  title: "Full Stack Web Developer",
  education: "BIM (Bachelor of Information Management)",
  university: "Tribhuvan University",
  location: "Nepal 🇳🇵",
  passion: "Building beautiful & functional web applications",
  
  skills: {
    frontend: ["HTML5", "CSS3", "JavaScript", "React", "Responsive Design"],
    backend: ["Node.js", "Express", "RESTful APIs"],
    database: ["MongoDB", "Firebase"],
    tools: ["Git", "GitHub", "VS Code", "Postman"]
  },
  
  currentlyLearning: "Advanced JavaScript & React Patterns, Full-Stack Development",
  openTo: "Collaborations, internships & exciting projects",
  
  quote: "Code today, inspire tomorrow ✨"
};
```

---

## 💻 Tech Stack

### 🌐 Frontend Technologies
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,responsive&perline=7" alt="Frontend Stack" />
</p>

### ⚙️ Backend Technologies  
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,firebase&perline=5" alt="Backend Stack" />
</p>

### 🛠️ Tools & Workflow
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,npm&perline=6" alt="Tools" />
</p>

---

## 📊 GitHub Statistics

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=gaurab72&show_icons=true&count_private=true&theme=react&border_color=0e75b6&bg_color=0D1117&title_color=0e75b6&icon_color=0e75b6&text_color=E8E8E8" alt="GitHub Stats" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gaurab72&langs_count=10&layout=compact&theme=react&border_color=0e75b6&bg_color=0D1117&title_color=0e75b6&text_color=E8E8E8" alt="Top Languages" />
</p>

<p align="center">
  <img width="60%" src="https://streak-stats.demolab.com?user=gaurab72&theme=react&hide_border=false&border_color=0e75b6" alt="GitHub Streak" />
</p>

---

## 🎯 Featured Projects

### 🔥 Highlight Your Best Work

| Project | Description | Technologies | Links |
|---------|-------------|---------------|-------|
| **Personal Portfolio** | Responsive portfolio website | React, Tailwind CSS | [🔗 Repo](#) \| [🌐 Live](#) |
| **CRUD Web App** | Full-stack todo application | Node.js, MongoDB, Express | [🔗 Repo](#) \| [🌐 Live](#) |
| **Weather Dashboard** | Real-time weather app | React, API Integration | [🔗 Repo](#) \| [🌐 Live](#) |

*👉 [View All Repositories](https://github.com/gaurab72?tab=repositories)*

---

## 🔥 Code Examples & Animations

### React Component with Smooth Animations
```jsx
// Beautiful animated component 🎨
import React, { useState } from 'react';

const AnimatedCard = () => {
  const [isActive, setIsActive] = useState(false);
  
  return (
    <div 
      className="card animate-fadeIn hover:scale-105 transition-all duration-300"
      onMouseEnter={() => setIsActive(true)}
      onMouseLeave={() => setIsActive(false)}
    >
      <h2 className="text-2xl font-bold text-blue-600">
        {isActive ? '✨ Interactive Component' : '👋 Hover Here'}
      </h2>
      <p className="animate-pulse">{isActive && 'Animation in action!'}</p>
    </div>
  );
};

export default AnimatedCard;
```

### Node.js Express Server
```javascript
// Fast & scalable backend API 🚀
const express = require('express');
const app = express();
const PORT = 5000;

// Middleware
app.use(express.json());

// Routes
app.get('/api/users', async (req, res) => {
  try {
    const users = await User.find();
    res.json({ success: true, data: users });
  } catch (error) {
    res.status(500).json({ error: error.message });
  }
});

app.post('/api/users', async (req, res) => {
  try {
    const newUser = await User.create(req.body);
    res.status(201).json({ success: true, data: newUser });
  } catch (error) {
    res.status(400).json({ error: error.message });
  }
});

app.listen(PORT, () => console.log(`🚀 Server running on port ${PORT}`));
```

### MongoDB Schema Example
```javascript
// Elegant data structure 📊
const mongoose = require('mongoose');

const userSchema = new mongoose.Schema({
  name: {
    type: String,
    required: true,
    trim: true
  },
  email: {
    type: String,
    required: true,
    unique: true,
    lowercase: true
  },
  skills: {
    type: [String],
    default: []
  },
  createdAt: {
    type: Date,
    default: Date.now
  }
});

module.exports = mongoose.model('User', userSchema);
```

---

## 📈 My Learning Journey

```
📚 Learning Roadmap:

2024:
  ✅ HTML5, CSS3, & JavaScript Fundamentals
  ✅ React Basics & State Management
  ✅ Node.js & Express Server Development
  ✅ MongoDB Database Design
  
2025:
  🎯 Advanced React Patterns & Hooks
  🎯 Full-Stack Application Architecture
  🎯 RESTful API Design & Best Practices
  🎯 Web Performance Optimization
  🚀 Contributing to Open Source
  🚀 Building Production-Ready Applications
```

---

## 🌟 What I'm Currently Doing

- 🔨 Building **responsive and interactive web applications**
- 📚 Learning **Advanced JavaScript** and **React patterns**
- 🎓 Pursuing **BIM degree** at Tribhuvan University
- 🤝 Open to **collaborations & internship opportunities**
- 💡 Contributing to **open-source projects**
- 🏆 Improving **problem-solving skills** through DSA practice

---

## 🎨 Skills Breakdown

### Frontend Mastery
- ✅ **HTML5** - Semantic markup & accessibility
- ✅ **CSS3** - Flexbox, Grid, Animations, Responsive Design
- ✅ **JavaScript** - ES6+, DOM manipulation, Event handling
- ✅ **React** - Components, Hooks, State Management, JSX
- ✅ **Responsive Design** - Mobile-first approach

### Backend Power
- ✅ **Node.js** - Server-side JavaScript runtime
- ✅ **Express.js** - Fast web framework
- ✅ **RESTful APIs** - Clean API design
- ✅ **Authentication** - User authentication & authorization

### Database & Tools
- ✅ **MongoDB** - NoSQL database design
- ✅ **Firebase** - Real-time database & authentication
- ✅ **Git & GitHub** - Version control
- ✅ **VS Code** - Code editor
- ✅ **Postman** - API testing

---

## 💬 Let's Connect!

<p align="center">
  <b>I'd love to hear from you!</b>
</p>

- 🤝 **Collaborations** on interesting projects
- 💼 **Internship & Job opportunities**
- 🎤 **Technical discussions** & knowledge sharing
- 🚀 **Open source contributions**
- 📧 **Any questions?** Feel free to reach out!

<p align="center">
  <a href="https://github.com/gaurab72" target="_blank">
    <img src="https://img.shields.io/badge/Follow%20on-GitHub-111827?style=for-the-badge&logo=github" alt="GitHub Follow" />
  </a>
  <a href="mailto:hamlgaurav80@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Send%20Me-Email-D14836?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/gaurab-hamal" target="_blank">
    <img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
</p>

---

## 🎨 Profile Features

This profile includes:
- ✨ **Animated typing effect** for dynamic headline
- 🌊 **Smooth visual hierarchy** with emojis & colors
- 📊 **Live GitHub statistics** with streak counter
- 🔥 **Code examples** with syntax highlighting
- 💻 **Technology showcase** with skill icons
- 🎯 **Clear learning roadmap** visualization
- 📈 **Interactive badges** & CTAs

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&duration=4000&pause=1000&color=0e75b6&center=true&vCenter=true&width=500&lines=Thanks+for+visiting+my+profile+%F0%9F%98%8A;Feel+free+to+star+%E2%AD%90+and+connect;Let's+build+amazing+projects+together+%F0%9F%9A%80" alt="Closing Message" />
</p>

<p align="center">
  <b>Made with ❤️ by Gaurab Hamal</b>
</p>
