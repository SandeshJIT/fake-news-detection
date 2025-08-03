# fake-news-detection

The rise of misinformation has become a serious issue in modern life in the digital age, influencing public opinion, elections, and health outcomes. As the internet and social media have become platforms where news websites thrive, it has become increasingly difficult for the average reader to determine whether a news report is real or not. [The ISOT Fake News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset) is a labeled news corpus of articles, which are marked as fake or real and therefore a fascinating resource to study how machine learning can be used to detect fake news automatically.  

The primary task is binary classification: developing models that can distinguish between real and fake news articles. But the project aims to do more than model with just high accuracy. Instead, we examine why models perform well whether they are learning useful patterns or simply finding dataset artefacts. Several problems raise themselves here:  
(1)  the subject column is very predictive and tends to leak the label.  
(2) text data is sparse and high-dimensional and so makes models overfitting or poorly generalizing prone.  
(3) date fields are randomly formatted and often missing and thus require thorough preprocessing. These issues need a methodical approach with equal focus on accuracy and other factors.  


# How to setup.
1. clone the repo and open on jupiter nodebook or google collab.
2. Download dataset from [The ISOT Fake News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset) and place in the root folder.
3. Insall the required dependencies if any missing.
4. Run each cell or run all cell at once and observe the results.
