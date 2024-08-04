# French Language Learning Conversation Simulator

This project implements a French language learning conversation simulator using Python and OpenAI's GPT model. It generates realistic conversations between a French learner and a tutor, incorporating common language mistakes and corrections.

## Features

- Generates synthetic user profiles for French language learners
- Simulates conversations with intentional language mistakes
- Provides tutor responses with gentle corrections and explanations
- Analyzes and categorizes different types of language errors

## Usage

1. Set up your OpenAI API key in your environment variables and install the packages in the `requirements.txt` file
2. Run the Jupyter notebook `extract.ipynb` to generate conversations and analyze mistakes.

## Key Components

- `LearnerProfile`: Pydantic model for generating synthetic learner profiles
- `SimulatedConversation`: Pydantic model for structuring the simulated conversations
- `Mistake`: Pydantic model for categorizing and explaining language mistakes
- `GrammaticalError` and `Vocabulary`: Subclasses of `Mistake` for specific error types

## Example Output

The notebook generates:

- Detailed learner backstories
- Simulated conversations with intentional mistakes
- Breakdown of mistakes made in the conversation
