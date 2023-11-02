# comment-toxicity-detecttion-
## Comment Toxicity is a project that uses deep learning to predict the toxicity of comments. The project is built using TensorFlow, NumPy, and Pandas frameworks. The deep neural network model uses an embedding layer as its input layer and TextVectorization to preprocess the input data.

The aim of the project is to predict the toxicity of comments in order to improve online conversations and make them more respectful and constructive. The model takes in comments as input and outputs a toxicity score, which is a value between 0 and 1 that indicates the degree of toxicity of the comment.

To achieve this, the project uses a deep neural network model that is trained on a dataset of comments labeled with their corresponding toxicity score. The model uses an embedding layer as its input layer, which converts the text data into a numerical representation that can be processed by the neural network. The TextVectorization function is used to preprocess the input data, which includes removing punctuation and stop words, lowercasing the text, and tokenizing the text into individual words.

The model is trained using a cross-entropy loss function and an Adam optimizer, which minimizes the loss function during training. The trained model is evaluated on a test set to measure its performance in terms of accuracy, precision, recall, and F1 score.
                                                   
The Comment Toxicity project can be used to analyze comments on various platforms and provide feedback to users on the toxicity of their comments. This can be used by moderators to improve the quality of online conversations and create a more respectful and positive online community.
 And the model is  deployed using Hugginng face spaces and gradio link https://huggingface.co/spaces/RohithMidigudla/Comment_Toxicity_Detection
