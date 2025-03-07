# StreamVerse Frontend

StreamVerse is a feature-rich movie streaming platform built with modern web technologies. This repository contains the frontend code for the StreamVerse project.

[![GitHub stars](https://img.shields.io/github/stars/LustyCodes/StreamVerse.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/immdpu/StreamVerse/stargazers/)
[![GitHub forks](https://img.shields.io/github/forks/LustyCodes/StreamVerse.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/LustyCodes/StreamVerse/network/)
[![GitHub issues](https://img.shields.io/github/issues/LustyCodes/StreamVerse.svg)](https://GitHub.com/LustyCodes/StreamVerse/issues/)
[![GitHub license](https://img.shields.io/github/license/LustyCodes/StreamVerse.svg)](https://github.com/LustyCodes/StreamVerse/blob/master/LICENSE)

## ⚠️ Disclaimer

This project is created for educational and practice purposes only. We do not store or host any movie data or content. All movie information is fetched from TMDB API, and any playback is done through third-party iframes. Please respect copyright laws and use this application responsibly.

## 🌟 Features

- User authentication and profile customization
- Movie and TV show browsing with TMDB API integration
- Watchlist and viewing history functionality
- Real-time global chat and private messaging
- Online user status indicators
- Responsive design for seamless mobile and desktop experience

## 🚀 Tech Stack

- [Next.js](https://nextjs.org/) - React framework for server-side rendering and routing
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Redux](https://redux.js.org/) - State management
- [React Query](https://react-query.tanstack.com/) - Data fetching and caching
- [Socket.IO](https://socket.io/) - Real-time, bidirectional communication

## 🛠 Installation

1. Clone the repository: `git clone https://github.com/LustyCodes/StreamVerse.git
2. Change directory: `cd StreamVerse`
3. Install dependencies: `npm install`
4. Create a `.env.local` file in the root directory and add the following environment variables:

```bash
BASE_URL=https://api.themoviedb.org"
NEXT_PUBLIC_BASE_URL="https://api.themoviedb.org"
NEXT_PUBLIC_LAN="en"
API_KEY="your_tmdb_api_key"
NEXT_PUBLIC_API_KEY="your_tmdb_api_key"
NEXT_PUBLIC_USER_URL="http://localhost:8080 or your deployed backend URL"
```

5. Start the development server:

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 🤝 Contributing

We welcome contributions to StreamVerse! Feel free to open issues and pull requests.

## 🔗 Related Repositories

- [StreamVerse Backend](https://github.com/LustyCodes/StreamVerse-backend) - The backend API for StreamVerse

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [TMDB](https://www.themoviedb.org/) for providing the movie and TV show data
- All the amazing open-source libraries and tools that made this project possible

---

⭐️ If you find StreamVerse interesting or useful, please consider giving it a star! It helps us know that our work is valued and encourages us to continue improving the project.
