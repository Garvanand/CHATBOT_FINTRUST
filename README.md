# Financial Issues Chatbot

A React-based financial/customer care chatbot powered by Groq's LLaMA AI. This application can process financial and personal documents through image analysis, analyze your queries, and provide detailed explanations in simple language.

<div align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/React-18.x-blue" alt="React">
  <img src="https://img.shields.io/badge/Node.js-14.x-green" alt="Node.js">
  <img src="https://img.shields.io/badge/Groq-LLaMA-orange" alt="Groq">
  <img src="https://img.shields.io/badge/Vercel-Deployed-brightgreen" alt="Vercel">
</div>



## Features

- 🎯 **Precise Analysis**: Accurate analysis of documents.
- 🗣️ **Voice Input Support**: Speak your queries instead of typing.
- 💬 **Interactive Chat Interface**: User-friendly chat interface.
- ✨ **Markdown Support**: Formatted responses for better readability.
- 🌓 **Dark/Light Mode**: Toggle between themes for comfortable usage.

### Unique Image Analysis Pipeline

This chatbot features a sophisticated document processing pipeline:

1. Upload a document image.
2. The image is processed directly by LLaMA's vision model.
3. The AI provides structured analysis of the image content.
4. Ask follow-up questions about specific aspects of the document.
5. The entire process happens seamlessly in real-time.

---

## Technologies Used

- **React.js**: Frontend framework.
- **Groq API**: LLaMA 3.3 70B & LLaMA 3.2 90B Vision models.
- **TailwindCSS**: Utility-first CSS framework.
- **React Markdown**: Render markdown in the chat interface.
- **React Icons**: Icons for UI elements.
- **Vercel Speed Insights**: Performance monitoring.

---

## Prerequisites

Before you begin, ensure you have:

- Node.js (v14 or higher)
- npm or yarn
- A Groq API key

---

## Installation

1. Clone the repository:
   ```bash
   git clone 
   cd CHATBOT_FINTRUST
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Groq API credentials:
   ```env
   REACT_APP_GROQ_API_KEY=your_api_key_here
   REACT_APP_GROQ_BASE_URL=https://api.groq.com/openai/v1
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The application will open in your default browser at `http://localhost:3000`.

---


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Garvanand/CHATBOT_FINTRUST/blob/main/LICENSE.txt) file for details.

---

## Acknowledgments

- **Groq**: For providing powerful LLaMA models.
- **React and its community**: For the excellent framework and tools.
- **Vercel**: For hosting and performance insights.

---

## Contact

For questions or feedback, reach out to [GARV ANAND](https://github.com/Garvanand).


---

## Support

⭐️ If you found this project helpful, please give it a star!

---



