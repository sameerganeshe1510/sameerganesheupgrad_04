# sameerganesheupgrad_04

## Fake_News_Detection_Assignment (classify news articles as Real & Fake News)

# Objective

This report presents the development and evaluation of a Semantic Classification system designed to detect fake news using Word2Vec embeddings and supervised learning algorithms. 
The objective is to move beyond surface-level syntax and instead classify news articles based on their semanticcontent—capturing the meaning and context of the text.


# The key goals are:

To implement an effective model that can accurately distinguish between true and fake news articles by analysing recurring linguistic patterns. This is achieved through:  
• Word2Vec for semantic feature extraction.  
• Supervised models (Logistic Regression, Decision Tree, Random Forest) for classification.  
• Robust preprocessing and exploratory data analysis to enhance model performance.  

# Conclusion

**Key Insights**:  
• True news articles use formal, institutional language, while fake news often relies on emotional,
dramatic or sensational wording.  
• N-gram analysis: True news focuses on structured governance and policy related words,
whereas fake news frequently includes visual and viral terms like “image” and “video”.

**Model Performance:**  
• Logistic Regression is the best performing model, with high evaluation metrics (91% accuracy)
and making it useful for identification of true news articles.  
• It indeed has a balanced evaluation metrics along with interpretability.  
• Useful for identifying true news and understanding feature influence.  
• Random Forest performed well too, especially in Recall (91%), though it lagged slightly behind
Logistic Regression in Precision and F1-score.  
• Decision Tree was relatively weaker in performance but was still able to provide reasonable
classifications.  

**Impact:**  
• The semantic classification approach, using Word2Vec embeddings and robust preprocessing,
effectively captures linguistic patterns to distinguish fake from true news.  
• The solution is scalable and adaptable to other misinformation domains.  


# Technologies used
numpy==1.26.4  
pandas==2.2.2  
nltk==3.9.1  
spacy==3.7.5  
scipy==1.12  
pydantic==2.10.5  
wordcloud==1.9.4  
