
# ✍️ AI-Powered Contextual Text Generation

An AI-powered text generation application built using Python, Streamlit, and GPT-2 language models. The application generates context-aware content for emails, essays, social media posts, stories, poems, and general-purpose writing.

## 🚀 Features

- 📧 **Email Generation:** Create professional emails with sender, receiver, subject, and purpose.
- 📝 **Essay Generation:** Generate essays based on a selected topic.
- 📱 **Social Media Posts:** Create engaging posts with emojis and hashtags.
- 📖 **Story Generation:** Generate creative stories from ideas and prompts.
- 🎭 **Poem Generation:** Create poems based on different themes.
- 💡 **General-Purpose Writing:** Generate text from custom prompts.
- ⚙️ **Model Selection:** Choose between GPT-2, GPT-2 Medium, and GPT-2 Large.
- 🎛️ **Customizable Output:** Adjust generation length and temperature.
- 📥 **Download Generated Text:** Save generated content as a text file.

## 🛠️ Technologies Used

- Python
- Streamlit
- Hugging Face Transformers
- GPT-2
- PyTorch

## 📂 Project Structure

```text
AI-Powered-Contextual-Text-Generation/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.10 or a compatible Python version
- Git
- An internet connection to download the pretrained model

### 1. Clone the repository

```bash
git clone https://github.com/KHYATIRAJ03/AI-Powered-Contextual-Text-Generation.git
cd AI-Powered-Contextual-Text-Generation
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🧠 How It Works

1. Select a text generation task.
2. Enter a topic, prompt, or the required email details.
3. Select a GPT-2 model size.
4. Adjust the maximum sequence length and temperature.
5. Click **Generate** to create the text.
6. Review the generated output and download it as a text file.

## 🎛️ Model Configuration

| Model | Description |
|---|---|
| GPT-2 | Original model; lower resource requirements |
| GPT-2 Medium | Larger model with increased resource requirements |
| GPT-2 Large | Larger model requiring substantially more memory |

Model performance and output quality vary depending on the prompt, available hardware, and generation settings.

## ⚠️ Limitations

- GPT-2 may generate inaccurate, repetitive, or irrelevant content.
- Generated text may require proofreading and editing.
- Larger models require more memory and processing power.
- The application uses pretrained language models and does not train a new model.
- Generated content should be reviewed before professional or academic use.

## 🔮 Future Enhancements

- Add additional language models.
- Improve prompt handling and output quality.
- Add copy-to-clipboard functionality.
- Introduce writing styles and tone selection.
- Add multilingual text generation.
- Improve deployment performance and user experience.

## 👩‍💻 Author

**Khyati Raj**

GitHub: [@KHYATIRAJ03](https://github.com/KHYATIRAJ03)
