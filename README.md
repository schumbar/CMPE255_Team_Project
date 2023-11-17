# CMPE255_Team_Project

CMPE255 Team Project for the Bay Area Rockers group consisting of Shawn Chumbar, Dhruval Shah, and Sajal Agarwal.

- Team Name: Bay Area Rockers

- Team Members: Shawn Chumbar, Dhruval Shah, and Sajal Agarwal

The project plan is transcribed below as markdown for ease of reading.

### Project Title

**Automated Summarization of Research Papers**

### Project Description

This project aims to develop an automated system for summarizing academic research papers, leveraging the power of Natural Language Processing (NLP) and deep learning. By implementing both extractive and abstractive summarization techniques, the project seeks to create concise, coherent summaries of lengthy research documents, facilitating easier comprehension and quicker review processes. Additionally, we plan to design a user-friendly web application that allows users to upload research papers in PDF format and receive summarized content.

### Objectives

1. **Develop an Extractive Summarization Model**: To identify and extract key sentences and phrases directly from research papers.
2. **Develop an Abstractive Summarization Model**: To generate concise paraphrased summaries that capture the essence of the research papers.
3. **Design a Web Application**: To provide a platform for users to easily upload PDF documents and obtain summaries.
4. **Compare and Analyze Performances**: To evaluate the effectiveness of both models in producing accurate and coherent summaries.

### Background

With the ever-increasing volume of academic literature, the ability to quickly comprehend and digest lengthy research papers is becoming crucial. Traditional manual summarization is time-consuming and labor-intensive. Automated text summarization using NLP and AI offers a promising solution, with potential to revolutionize the way researchers and academics interact with literature.

### Methodologies

1. **Data Collection**: Accumulating a dataset of over 50 research papers, each with corresponding summaries.
2. **Data Preprocessing**: Cleaning and preparing the text data for model training.
3. **Model Training**:
    - **Extractive Model**: Training a model like BertSum to identify key sentences in the text.
    - **Abstractive Model**: Utilizing models like BART or T5 to generate paraphrased summaries.
4. **Model Evaluation**: Assessing the models using metrics like ROUGE (Recall-Oriented Understudy for Gisting Evaluation).

### Technology to be Used

- **Hugging Face’s Transformers**: For pre-trained NLP models.
- **PyTorch or TensorFlow**: As the deep learning framework.
- **Google Colab**: For leveraging GPU resources for training and testing models.
- **Python**: As the primary programming language.
- **Web Development Frameworks**: Such as Flask or Django for building the web application.
- **Front-End Technologies**: Like HTML, CSS, and JavaScript for developing the user interface.

### Expected Outcomes

- **Effective Summarization**: The ability to produce summaries that are both concise and representative of the original texts.
- **Model Comparison**: Insights into the comparative effectiveness of extractive vs. abstractive summarization techniques.
- **Scalability**: A framework that can be adapted for summarizing papers across various academic disciplines.

### Project Deliverables

1. **Trained Models**: The final trained extractive and abstractive models.
2. **Codebase**: All code developed for the project, including data preprocessing, model training, and evaluation scripts.
3. **Documentation**: Comprehensive documentation detailing the methodologies, usage, and evaluation of the models.
4. **Project Report**: A detailed report outlining the project execution, findings, and analysis.
5. **Web Application**: A functional web platform for users to upload PDFs and receive summaries.
### Conclusion

This project aims to contribute significantly to the field of NLP by addressing the challenge of automated research paper summarization. The successful implementation of this project will not only demonstrate the capabilities of current AI and NLP technologies in understanding and processing complex academic texts but also pave the way for future advancements in automated text summarization.