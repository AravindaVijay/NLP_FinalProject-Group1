# Welcome to All Resume Solutions

This repository provides comprehensive solutions for all your resume-related needs. Our tools are designed to assist both job seekers and hiring teams in various aspects of resume creation, analysis, and evaluation.

## Features

1. Resume matching with job descriptions
2. Resume analysis
3. Job description analysis
4. Resume grammar and formatting checker
5. Rank resumes based on job descriptions (helpful for hiring teams)
6. Resume generation for specific jobs

## Installation

To get started with All Resume Solutions, follow these steps:

1. **Clone the repository** to your local system:
   ```
   git clone https://github.com/AravindaVijay/NLP_FinalProject-Group1.git
   ```
   Note: Please initialise git lfs before cloning as the model files are large. 
   
3. **Navigate to the project directory** using the terminal. Alternatively, you can directly open the project in your IDE (e.g., VSCode or PyCharm).

4. **Install the required dependencies** by running the following command:
   ```
   pip install -r requirements.txt
   ```

**Note- For the grammer checker to work please update the API keys -AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_SESSION_TOKEN and REGION_NAME in mentioned variables in the streamlitApp.py**
 
## Usage

To run the Streamlit app, use the following command in your terminal:

```bash
streamlit run streamlitApp.py
```

Now you can explore the app by uploading your resume and job description to get detailed scores, grammar checks, formatting analysis, and much more.

## For Developers

We've created two distinct pipelines to help you generate custom embeddings for resumes and job descriptions, allowing you to train your own models.

### 1. DataExtractionProject

**Steps to Extract and Prepare Data:**

1. Navigate to the DataExtractorProject directory:
   ```bash
   cd DataExtractorProject
   ```

2. Use your own dataset or utilize the pre-existing JSON file from Hugging Face.

3. Run the data extraction script:
   ```bash
   python3 main.py
   ```

4. After execution, you'll have a converted resume text JSON that can be used for semantic analysis or model training.

### 2. ResumeJobScore

**Model Training and Embedding Generation:**

1. Move to the ResumeJobScore directory:
   ```bash
   cd ResumeJobScore
   ```

2. The main file offers two code paths:
   - To create embeddings: Comment out the model training section.
   - To train a model: Do the opposite.

3. Run the entire pipeline:
   ```bash
   python3 main.py
   ```

**Note:** 
- The dataset in the repository is large and might require GPU support for training and embedding generation.
- Adjust the code according to your specific requirements and computational resources.

Happy Coding! 🚀



## Contributing

We welcome contributions to All Resume Solutions! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details on how to submit pull requests, report issues, or request features.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, please open an issue in this repository or contact the maintainers directly.

## Acknowledgements

- List any libraries, tools, or resources you've used or been inspired by
- Credit any collaborators or contributors








