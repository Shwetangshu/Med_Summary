# Medical SOAP Summary Generator

This repository contains code for generating medical SOAP (Subjective, Objective, Assessment, Plan) summaries using transformer-based language models.

## Installation

To install the necessary dependencies, run:

```bash
pip install transformers
pip install accelerate
pip install -i https://pypi.org/simple/ bitsandbytes
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Shwetangshu/Med_Summary.git
cd Med_Summary
```

2. Open the Python Notebook `Med.ipynb` in Google Colab.

3. Run the notebook cells to execute the code.

4. Follow the instructions to input the dialogue for which you want to generate a SOAP summary.

## Model

The SOAP summaries are generated using the `omi-health/sum-small` transformer-based language model, fine-tuned for medical text summarization tasks.

## Credits

This project utilizes the Hugging Face `transformers` library for accessing pre-trained transformer models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
