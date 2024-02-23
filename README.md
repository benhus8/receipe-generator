# Grocery Chef

## Overview
This project is designed to assist users in generating cooking recipes based on the ingredients they have at hand. It utilizes natural language processing (NLP) models for language translation and recipe generation. The project supports translation between English and Polish languages and can generate recipes based on the provided ingredients.

## Features
1. **Translation**: The project can translate ingredient lists between English and Polish languages using state-of-the-art machine translation models.
2. **Recipe Generation**: Using a recipe generation model, the project can generate cooking recipes based on the provided ingredients in the preferred language.
3. **User Interaction**: Users can interact with the project by providing input in the form of a list of ingredients, and they will receive a corresponding recipe.

## Usage
1. **Setup**: Install the required dependencies by following the instructions in the provided Jupyter Notebook.
2. **Input**: Declare your preferred input language (`language_cd`) and list all available grocery items (`items`).
3. **Translation**: If necessary, translate the grocery items list to the desired language using the provided translation functions.
4. **Recipe Generation**: Utilize the recipe generation function to generate cooking recipes based on the provided ingredients.
5. **Output**: The generated recipes will be displayed, and if needed, they can be translated back to the original language.

## Requirements
- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python packages (listed in the notebook)
- Internet connection for model downloads and translations

## Credits
This project utilizes models from the Hugging Face Transformers library and Flax Community. 

## License
This project is licensed under the MIT License.
