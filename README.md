# GitHubLens 🔍

[![Live Demo](https://img.shields.io/badge/LIVE-DEMO-brightgreen?style=for-the-badge)](https://mohan13krishna.github.io/GitHubLens/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/mohan13krishna/GitHubLens)

<div align="center">
  <p><em>Bringing GitHub profiles into perfect focus, instantly.</em></p>
</div>

## ✨ Overview

GitHubLens is a powerful yet elegantly simple web application that allows you to explore GitHub profiles with crystal clarity. With just a username search, instantly reveal comprehensive profile information and discover a user's top repositories in a beautifully designed interface.

**[Try it now! →](https://mohan13krishna.github.io/GitHubLens/)**

## 🚀 Key Features

- **Instant Profile Discovery** - Type a username and immediately see their GitHub presence
- **Complete Profile Details** - View avatar, name, bio, follower stats, and more at a glance
- **Top Repository Showcase** - Explore the 5 most recent repositories with direct GitHub links
- **Responsive Design** - Perfect experience on any device, from mobile to desktop
- **Clean, Modern UI** - Enjoy a beautiful dark theme interface with intuitive navigation
- **Real-time API Integration** - Fetch current data directly from GitHub's REST API

## 🖥️ Technologies

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/GitHub_API-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub API">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios">
</div>

## 📱 Preview

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Desktop View</strong></td>
      <td align="center"><strong>Mobile View</strong></td>
    </tr>
    <tr>
      <td><img src="https://i.imgur.com/placeholder-desktop.png" alt="Desktop Preview" width="450px"></td>
      <td><img src="https://i.imgur.com/placeholder-mobile.png" alt="Mobile Preview" width="200px"></td>
    </tr>
  </table>
</div>

## 🔧 Installation & Usage

### Quick Start:
Simply visit the [live demo](https://mohan13krishna.github.io/GitHubLens/) and start searching!

### Local Development:
```bash
# Clone the repository
git clone https://github.com/mohan13krishna/GitHubLens.git

# Navigate to the project directory
cd GitHubLens

# Open in your browser
# Simply open index.html or use a local server like Live Server in VS Code
```

## 💡 How To Use

1. **Search** - Enter a GitHub username in the search box
2. **Discover** - Instantly view their profile details
3. **Explore** - Click on any repository to open it on GitHub
4. **Repeat** - Search for another user anytime

## ⚙️ Under The Hood

GitHubLens uses the GitHub REST API to fetch real-time user data. When you search for a username:

1. The application makes an API call to `https://api.github.com/users/{username}`
2. Upon success, it displays the user profile and makes a second call to fetch repositories
3. The top 5 most recently created repositories are then displayed with direct links
4. All of this happens with smooth error handling and a seamless user experience

## 🤝 Contributing

Contributions are welcome! Feel free to enhance GitHubLens:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Mohan Krishna** - [GitHub Profile](https://github.com/mohan13krishna)

## 🌟 Star the Repository

If you find GitHubLens useful, consider giving it a star on GitHub to show your support!

[![GitHub stars](https://img.shields.io/github/stars/mohan13krishna/GitHubLens?style=social)](https://github.com/mohan13krishna/GitHubLens/stargazers)

---

<div align="center">
  <p>Developed with ❤️ by <a href="https://github.com/mohan13krishna">Mohan Krishna</a></p>
  <p>
    <a href="https://github.com/mohan13krishna/GitHubLens/issues">Report Bug</a> •
    <a href="https://github.com/mohan13krishna/GitHubLens/issues">Request Feature</a>
  </p>
</div>
