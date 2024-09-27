# 🌟Live Code Editor 🚀 [Live Demo](https://leetcode-ide.vercel.app/)

Welcome to the **Live Code Editor**, a full-fledged real-time code editor inspired by Leetcode! This project showcases my expertise in full-stack development using modern technologies, focusing on both frontend and backend integration. It supports multiple programming languages, user input, and displays results just like the original Leetcode platform.

<p align="center">
  <img src="https://user-images.githubusercontent.com/64205626/176822891-187fb3b9-f3b4-429f-ace7-2f937ac0f23d.png" width="600"/>
</p>

## 📽️ Project Demo
[Live](https://leetcode-ide.vercel.app/)

## 🚀 Features

- 🔥 **Multiple Language Support**: Compile and execute code in various programming languages.
- 🎨 **Custom Themes**: Choose from multiple editor themes to suit your coding style.
- 🧮 **Real-time Code Execution**: Get instant feedback on your code execution.
- 💾 **Code Input/Output Handling**: Easily input test cases and view the corresponding output.

## 🏗️ Project Versions

### 🌱 Version 1

The initial version of the project was built with:

- **Frontend**: React.js (client folder)
- **Backend**: Node.js & Express.js (backend folder)
- **Editor**: Multiple themes, language support, input, and output sections.

### Folder Structure Overview:

```bash
├── client
│   ├── app.js           # Main homepage
│   ├── components/
│   │   ├── CodeEditor   # The editor interface
│   │   ├── CodeInput    # Input section for test cases
│   │   ├── CodeOutput   # Output/result section
│   │   └── Navbar       # Navbar with Run Code & theme options
│   └── lib/defineTheme.js  # Custom theme definitions
│   └── boilerCodes/     # Initial code templates for various languages
├── backend
│   ├── index.js         # Main backend server
│   ├── routes.js        # Backend API for code execution
│   └── utils/
│       ├── generateCodeFile.js  # Generates code and input files for execution
│       └── executeCodeFile.js   # Runs the code via Node's exec process
```

---

### 🚧 **Version 2 - Using RapidAPI & Judge0** ⚡

In this version, I've integrated **Judge0 API** via **RapidAPI** for remote code compilation and execution, supporting multiple languages. 

---

## 🛠️ Future Enhancements & To-Do List

- [ ] 🔨 **Boilerplate Code**: Add default boilerplate code for all languages.
- [ ] 📁 **Code Snippets**: Save user code snippets with keywords for easy access.
- [ ] 💾 **Code Saving**: Allow saving code to the local system.
- [ ] 🔗 **Persistent Code Storage**: Save the current session in `localStorage` to prevent data loss on reload.

### Planned Features

- [ ] 🔐 **User Authentication**: Implement authentication to allow users to save personalized settings.
- [ ] ⚙️ **User Settings**: Let users manage personal preferences and code snippets.
- [ ] 🚀 **More Features**: Many more enhancements and performance improvements.

---

## 💻 How to Run Locally?

Follow these steps to run the project on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/leetcode-ide.git
   cd leetcode-ide
   ```

2. **Set up the environment**:

   - Go to [Judge0-rapidApi](https://rapidapi.com/judge0-official/api/judge0-ce/) and sign up if needed.
   - Create a `.env` file in the root directory and add the following keys:

   ```env
   REACT_APP_RAPID_API_HOST = <X-RapidAPI-Host>
   REACT_APP_RAPID_API_KEY = <X-RapidAPI-Key>
   REACT_APP_RAPID_API_URL = <X-RapidAPI-Host/submissions>
   ```

3. **Install dependencies**:
   ```bash
   npm install
   cd client && npm install
   cd ../backend && npm install
   ```

4. **Run the app**:

   - Start both the frontend and backend servers:

   ```bash
   cd client && npm start
   cd ../backend && node index.js
   ```

---

## 🤝 Contribution

Feel free to fork this repository, raise issues, or suggest new features by submitting a PR.

---

⚡ **This project is a great demonstration of my full-stack development skills, integrating real-time code execution, a modern frontend, and backend API development. Let's build something amazing together!** ✨
