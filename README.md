# Extraction-of-Imperatives-aka-Policies-using-NLP
• Built an NLP model to extract Imperatives(Policies as per use case scenario) from a given text.
• Hugging Face Transformers were used to build a summarisation model based on the use case of extracting
imperatives by training model on custom dataset consisting of text and its corresponding imperatives.
• The current model was built by choosing a Pre Tarined model which best fits our use case, and training it with our
custom dataset.
Training.ipynb file consists training notebook where we have applied transfer learning technique to achieve our goal of extracting imperatives from a given text.
train.json consists example dataset used to train our model.
Policyxtractor.ipynb consist of various functions like extracting text from a pdf file, splitting it into chunks, processing the extracted data to fit the model we built.
