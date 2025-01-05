# Gemini Clone 🤖

A React-based clone of Google's Gemini AI interface, built with modern web technologies and styled using Tailwind CSS.

## 🌟 Features

- Real-time AI responses using the Gemini API
- Clean and responsive user interface
- Chat history management
- Code highlighting for programming responses
- Markdown support for formatted text
- Mobile-friendly design

## 🛠️ Tech Stack

- **Frontend Framework:** React.js
- **Styling:** Tailwind CSS
- **API Integration:** Google Gemini API
- **Code Highlighting:** Prism.js
- **Markdown Support:** React-Markdown
- **Build Tool:** Vite

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Google Cloud Platform account
- Gemini API key

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Aditya1or0/gemini-clone.git
cd gemini-clone
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Create a `.env` file in the root directory:

```env
VITE_GEMINI_API_KEY=your_api_key_here
```

4. Start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

## 📝 Environment Variables

Create a `.env` file with the following variables:

```env
VITE_GEMINI_API_KEY=your_api_key_here
```

## 🔧 Configuration

### Gemini API Setup

1. Visit the [Google Cloud Console](https://console.cloud.google.com)
2. Create a new project or select an existing one
3. Enable the Gemini API
4. Create API credentials
5. Copy the API key to your `.env` file

## 📦 Project Structure

```
└── Aditya1or0-gemini-clone/
    ├── README.md
    ├── eslint.config.js
    ├── index.html
    ├── package.json
    ├── vite.config.js
    ├── public/
    └── src/
        ├── App.jsx
        ├── index.css
        ├── main.jsx
        ├── assets/
        │   └── assets.js
        ├── components/
        │   ├── Main/
        │   │   ├── Main.css
        │   │   └── Main.jsx
        │   └── Sidebar/
        │       ├── Sidebar.css
        │       └── Sidebar.jsx
        ├── config/
        │   └── gemini.js
        └── context/
            └── Context.jsx
```

### Directory Structure Explanation

- `src/components/`: Contains the main UI components
  - `Main/`: Houses the main chat interface
  - `Sidebar/`: Contains the sidebar navigation and chat history
- `src/config/`: Contains configuration files for the Gemini API
- `src/context/`: Contains React context for state management
- `src/assets/`: Stores static assets and asset utilities

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Google Gemini API team for providing the API
- React.js community for excellent documentation
- Tailwind CSS team for the amazing styling framework

## 📞 Contact

Aditya - [@Aditya1or0](https://github.com/Aditya1or0)

Project Link: [https://github.com/Aditya1or0/gemini-clone](https://github.com/Aditya1or0/gemini-clone)
