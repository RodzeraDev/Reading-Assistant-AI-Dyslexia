# Readable

Readable is an AI tool that simplifies text for people with reading issues, mainly dyslexia. It uses real data to make sure the text is not just randomly simplified, but instead tailored specifically for these types of needs rather than just a spin-off ChatGPT. Feedback is used to further improve the tool.

# Feature List

- AI backend that simplifies the text
- Rule set to interact with specific types of sentences and words
- Feeback system with thumbs up/down
- Readability evaluation
- Web interface


# Quick start:
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn app:app --reload