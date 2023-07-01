# CNN Assignment: Genre Prediction from Book Covers

any changes i made on the template code is marked vit a "# comment" in the code
In the context of this data-driven modeling project, I engaged with a dataset comprising numerous book covers, with the objective of predicting each book's genre. This project significantly enhanced my understanding of Convolutional Neural Networks (CNNs) and neural networks in general.

## CNN Approach

Utilizing a supervised machine learning algorithm, I implemented a Convolutional Neural Network (CNN) to predict book genres based on their covers. The CNN was trained on a dataset of labeled book covers, each label representing the book's genre. During the learning process, the CNN autonomously learned to extract pertinent features from the book cover images to assist in genre prediction.

experimentsoftmaxVGG19 is my worst approch which completely failed. I dont fully know why, but all gets predicted in class 16 but another time i ran it (like seen in my presentation) it was in class 2. I assume it always gives a different class each time i run the model.

## Fine-Tuning Approach

Aware of the limitations of a CNN without a pre-trained model, I initially set the algorithm to run for two epochs. Promptly, I began experimenting with pre-trained models, fine-tuning them to suit my needs. This approach not only accelerated the process but also markedly improved the accuracy of the predictions.

## Comparison with Kaggle's Best

The top performance on Kaggle reached a 40% accuracy, whereas my model achieved approximately 17%. I attribute this discrepancy primarily to my relatively minimal efforts in fine-tuning.

## Learnings from my Project

Several key insights emerged from this project:

1. Unless one has infinite resources and a compelling reason, it is generally unadvisable to attempt to train a model from scratch.
2. When working with complex pre-trained models or conducting extensive fine-tuning, ensuring the GPU is active is crucial to avoid overloading the CPU.
3. The Keras library is a valuable tool, as manually loading images can quickly consume available RAM.
4. Initial testing should be conducted on a small dataset before progressing to the full dataset for prototyping.
5. Researching pre-trained models before deployment is crucial to avoid mishaps. For instance, deploying the VGG19 model maxed out my CPU for 150 minutes and eventually resulted in an error upon completion.
6. It's important to note that different IDEs function differently - for instance, PyCharm has autosave active by default, unlike Visual Studio Code (VSC).

Overall, this project offered a satisfying learning experience, and I am grateful for the opportunity it provided to grow and learn.

written by me, formating gpt(slight wording change)
