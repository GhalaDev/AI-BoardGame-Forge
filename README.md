# AI BoardGame Forge

## Preview

![Preview](assets/preview.png)

## Live Demo

Try the application here:

[Launch AI BoardGame Forge](https://huggingface.co/spaces/GhalaDev/AI_BoardGames_Forge)


AI BoardGame Forge is an AI-powered web application that uses a Large Language Model (LLM) to generate complete board game concepts from any user-provided theme. It creates game rules, unique cards, and AI-generated artwork through an interactive Gradio interface.

The application automatically generates:

- A game title
- A game description
- Simple game rules
- Four unique game cards
- AI-generated artwork for every card
- Professionally styled trading card layouts

The project is designed as a beginner-friendly AI application and was developed in Python using Gradio.

---

## Features

- Generate complete board games using an LLM
- Create game titles, descriptions, and rules
- Generate structured game data in JSON format
- Create unique game cards with names, types, and abilities
- Generate AI artwork for each card
- Design trading-card layouts using Pillow
- Interactive Gradio web interface
- Easy to run in Google Colab

---

## Technologies Used

- Python
- Gradio
- Hugging Face Transformers
- Qwen2.5-0.5B-Instruct
- PyTorch
- Pillow (PIL)
- Requests
- Pollinations AI
- Google Colab

---

## How It Works

The application follows a simple pipeline:

1. The user enters a custom game theme.
2. The Qwen language model generates the game in structured JSON format.
3. The application extracts the game title, description, rules, and cards.
4. Pollinations AI generates artwork for each card.
5. Pillow creates styled trading-card layouts.
6. Gradio displays the generated game and card gallery.

---

## Project Structure

```
AI-BoardGame-Forge/
│
├── AI BoardGame Forge LLM.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/GhalaDev/AI-BoardGame-Forge.git
cd AI-BoardGame-Forge
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install gradio pillow requests
```

---

## Running the Project

Open the notebook in Google Colab or Jupyter Notebook and run all cells.

The Gradio application will launch and provide an interactive interface for generating AI-powered board games.

---

## Example Themes

- Space Cats
- Ancient Pirates
- Cyber Ninjas
- Lost Kingdom
- Underwater Civilization
- Robot Revolution
- Medieval Fantasy
- Haunted Mansion

---

## Future Improvements

- Support larger card decks
- Add multiplayer game mechanics
- Export games as PDF
- Save generated games locally
- Improve card balancing
- Add downloadable card packs

---

## License

This project is intended for educational purposes.
