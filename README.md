# Moroccan Consulate Assistant 🇲🇦

An AI-powered chatbot assistant that helps users navigate the Moroccan Consulate website services. This interactive assistant guides users through account creation, appointment booking, document submission, and visit scheduling processes.

## 🌟 Features

- **Step-by-step guidance** for consulate services
- **Interactive chat interface** powered by OpenAI's GPT-4o-mini
- **Comprehensive support** for:
  - Account creation and login
  - Appointment requests
  - Service selection and beneficiary management
  - Document upload and submission
  - Visit scheduling and preparation
- **Real-time streaming responses** for better user experience
- **Web-based interface** using Gradio

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- OpenAI API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/moroccan-consulate-assistant.git
   cd moroccan-consulate-assistant
   ```

2. **Install required packages**
   ```bash
   pip install openai gradio python-dotenv
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the project root:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Run the application**
   ```bash
   jupyter notebook moroccan_consulate_assistant.ipynb
   ```
   
   Or convert to Python and run directly:
   ```bash
   jupyter nbconvert --to python moroccan_consulate_assistant.ipynb
   python moroccan_consulate_assistant.py
   ```

## 📖 Usage

1. **Start the application** - The Gradio interface will launch automatically
2. **Access the chat interface** at `http://127.0.0.1:7860`
3. **Ask questions** about consulate services such as:
   - "How do I create an account?"
   - "What documents do I need for a passport renewal?"
   - "How do I schedule an appointment?"
   - "What should I bring on my visit day?"

## 🏗️ Project Structure

```
moroccan-consulate-assistant/
├── moroccan_consulate_assistant.ipynb  # Main Jupyter notebook
├── .env                                # Environment variables (create this)
├── README.md                          # Project documentation
└── requirements.txt                   # Python dependencies
```

## 🤖 AI Assistant Capabilities

The assistant provides guidance on:

### Account Management
- Account creation process
- Login procedures
- Password requirements and recovery

### Appointment Services
- New application submission
- Beneficiary management
- Service selection based on age and residence status

### Document Handling
- Required document identification
- Upload procedures
- Original document requirements

### Visit Preparation
- Appointment confirmation
- Required items checklist
- Arrival procedures

## 🛠️ Technical Details

- **AI Model**: OpenAI GPT-4o-mini
- **Interface**: Gradio ChatInterface
- **Streaming**: Real-time response streaming
- **Environment**: Jupyter Notebook compatible

## 🔒 Security

- API keys are stored in environment variables
- No sensitive data is logged or stored
- All interactions are processed securely through OpenAI's API

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📞 Support

For questions about consulate services, the assistant will direct you to:
- Your consular space "My request" option
- Consular Call Center
- Official website: www.consulat.ma

For technical issues with this project, please open an issue on GitHub.

## ⚠️ Disclaimer

This is an unofficial assistant tool. For official information and services, always refer to the official Moroccan Consulate website and resources.

## 🙏 Acknowledgments

- OpenAI for providing the GPT-4o-mini model
- Gradio team for the excellent chat interface framework
- Moroccan Consulate for the service information structure

---

**Made with ❤️ to help the Moroccan community navigate consulate services more easily**
