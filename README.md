Cyberbully Detection in Texts, Images and Audios

Table of Contents Introduction Features Installation Usage Evaluation
Metrics Conclusion Future Work References Introduction Cyberbullying
Detection using Machine Learning is a research project aimed at
identifying cyberbullying instances in various forms of media, including
text, images, and audio. The project utilizes machine learning
algorithms, specifically an ensemble approach combining Bidirectional
LSTM and Convolutional Neural Network (CNN) models, to achieve effective
detection of cyberbullying behavior in online content.

![Flow of Events](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/9b0049ef-0c40-488a-beae-6b72951891c4)

Features Detection of cyberbullying in text, images, and audio Ensemble
approach combining Bidirectional LSTM and CNN models for improved
accuracy Evaluation using various metrics, including accuracy,
precision, recall, and confusion matrix Potential extension to include
video data for real-time analysis

Open the Jupyter notebook containing the code for text, image, and audio
analysis.

Prepare your dataset of labeled cyberbullying and non-cyberbullying
content in text, image, and audio formats.

Run the cells in the Jupyter notebook to train the models on the
provided dataset.

The evaluation metrics, including accuracy, precision, recall, and
confusion matrix, will be displayed within the notebook.

Evaluation Metrics The project utilizes the following evaluation metrics
to assess the models' performance:

Accuracy: Percentage of correctly classified samples out of the total
number of samples.

![Acc_pre_bar_epochs](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/0fd407ca-1e90-4c4c-8ed5-5ee833dcadf4)

Precision: Proportion of true positive predictions to
all positive predictions. Recall: Number of true positive predictions
out of all genuine positive forecasts. 

![Text_Metrics_vs_epochs](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/d95b4433-0af2-47cb-a416-bb5b156409a5)

Confusion Matrix: Visual
representation of the true and predicted labels for the test data.
Conclusion The Cyberbullying Detection using Machine Learning project
demonstrates the effectiveness of text and image models in detecting
cyberbullying in online content. The ensemble approach combining
Bidirectional LSTM and CNN models achieves high accuracy and precision
in identifying cyberbullying instances. 

![Confusion_matrix_text](https://github.com/saiteja007-mv/Cyberbully-Detection-in-Texts-Images-and-Audios/assets/56865372/b49a37c2-ecc4-4f92-87b9-5e1a9fbd5f36)

However, the project
acknowledges certain limitations and suggests potential future work to
enhance detection capabilities, particularly in the context of video
data analysis.

Future Work The project proposes expanding the detection approach to
include video data, utilizing techniques such as object and action
recognition, facial recognition, audio analysis, and context analysis.
Incorporating real-time processing techniques and training machine
learning algorithms on large datasets of cyberbullying videos could lead
to more effective systems for identifying cyberbullying behavior.

References V. Subrahmanian and S. Kumar, "Predicting human behavior: The
next frontiers," Science, vol. 355, no. 6324, p. 489, 2017. H. Lauw, J.
C. Shafer, R. Agrawal, and A. Ntoulas, "Homophily in the digital world:
A live Journal case study," IEEE Internet Comput., vol. 14, no.2, pp. 15
– 23, Mar./Apr. 2010. A Hybrid Model for Cyberbullying Detection on
Facebook" by Arindam Mandal, Sriparna Saha, and Alexandar Ferworn.
