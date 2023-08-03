# Project Title: AI-Powered Resume Screening System for Optimal Candidate Selection


# Project Description:
The "Resume Selection Model" is a data-driven solution aimed at assisting recruiters and hiring managers in identifying the most suitable job candidates from a pool of resumes. By leveraging natural language processing (NLP) techniques and machine learning algorithms, this project streamlines the resume screening process, saving valuable time and resources for hiring teams.

# Key Project Steps:

    Exploratory Data Analysis (EDA): Extensive EDA was conducted on the dataset, unraveling valuable insights into candidate qualifications and resume contents. The target variable indicating selection status (flagged or unflagged) was examined to understand the distribution of candidates.

    Data Preprocessing and Label Encoding: The target variable representing resume selection status was label-encoded to facilitate binary classification. Furthermore, data cleaning techniques were applied to eliminate noise, such as stop words and irrelevant information.

    Text Preprocessing with Gensim: Utilizing the powerful Gensim library, the textual data from the resume column underwent tokenization of sentences and words. This step transformed the resumes into meaningful units for further analysis.

    Visualizing Word Clouds: Word clouds were generated for flagged and unflagged resumes, offering visual representations of frequently occurring keywords in each category. These visualizations assisted in understanding the key attributes associated with selected and non-selected candidates.

    Vectorization with CountVectorizer: To enable efficient text analysis, the textual data was converted into a vectorized format using CountVectorizer, a widely-used NLP technique.

    Model Training and Prediction: Employing the Naive Bayes classifier, the machine learning model was trained on the vectorized resume data to predict whether a candidate's resume would be flagged or unflagged for further consideration.

    Evaluation Metrics: Confusion matrices and classification reports were generated to evaluate the model's performance on both the training and test datasets. Precise metrics, including accuracy, precision, recall, and F1-score, provided comprehensive insights into the model's effectiveness.
