# Finetuning_Idefics_9B

# Pokémon Card Image-Caption Finetuning in Google Colab 

This notebook demonstrates how to finetune the IDEFICS 9B model on a dataset of Pokémon cards to generate image descriptions.

**Key Libraries**

* datasets (Hugging Face)
* transformers (Hugging Face)
* peft (Hugging Face)
* BitsAndBytes
* PIL (for image processing)

**Dataset**

This notebook utilizes the "TheFusion21/PokemonCards" dataset from Hugging Face Datasets.

**Model and Finetuning**

1. **Base Model:** IDEFICS 9B (HuggingFaceM4/idefics-9b) 
2. **Finetuning Approach:**  PEFT (Lora)
3. **Quantization:** BitsAndBytes for efficient training and inference.

**Code Structure**

* **Installation:** Cells for installing necessary libraries.
* **Data Loading and Preprocessing:** Cells for loading the Pokémon dataset, creating prompts, and applying image transformations.
* **Model Setup and Finetuning:**  Cells defining the model, configuration, and the training loop (using the `Trainer` class).
* **Inference:** Cells demonstrating how to generate a text description for a new Pokémon card image.

**To Run the Notebook**

1. Open this notebook in Google Colab.
2. Ensure you have a GPU-enabled runtime selected.
3. Execute the cells in order. 
