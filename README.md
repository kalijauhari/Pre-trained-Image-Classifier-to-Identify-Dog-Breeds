Identifying Dog Breeds using Pre-trained Image Classifier

🐶 Welcome to the my AI Programming with Python Nanodegree project at Udacity, where we embark on an exciting journey to classify dog breeds using a powerful pre-trained deep learning model. Let's build a command-line application that effortlessly categorizes images of dogs into various breeds.

📚 Project Overview

The project comprises the following key components:

🔍 check_images.py: The heart of our application, this script serves as the main entry point. By providing command-line arguments, you can specify the directory containing the images, the pre-trained model architecture you wish to employ, and the file that contains the dog breed labels.

💡 Pre-trained Model: Our application harnesses the power of a pre-trained deep learning model to accurately classify the images. While the default model architecture is VGG, you can easily switch to a different one using the --arch command-line argument.

📝 Dog Breed Labels: To enhance our classification process, we rely on a file (dognames.txt by default) that contains an extensive list of dog breed labels. These labels play a crucial role in accurately classifying the images and displaying the predicted breed.

💻 Getting Started

To get started with this captivating project, follow these steps:

1️⃣ Clone the project repository: [GitHub Repository](https://github.com/udacity/AIPND-revision)

2️⃣ Install the required dependencies: Seamlessly install the necessary dependencies by executing the command pip install -r requirements.txt. Let the magic begin!

3️⃣ Download the pre-trained model weights: Elevate your application by downloading the pre-trained model weights and placing them in the model_weights directory. You can find the download link in the project instructions. Prepare for excellence!

4️⃣ Run the script check_images.py: Witness the power of AI in action by running the script with your desired command-line arguments.

🎯 Command-line Arguments

This application supports the following command-line arguments:

--dir: Unleash the potential by specifying the directory of the images to be classified. Default: pet_images/.

--arch: Empower your application with the pre-trained model architecture of your choice. Default: vgg.

--dogfile: Fuel the classification engine by specifying the file containing the dog breed labels. Default: dognames.txt.

📊 Results

Prepare to be amazed! After running the script, our application will reveal impressive results, including the number of images processed, the percentage of correct matches, the accuracy of dog classifications, the precision of breed classifications, and even the accuracy of identifying non-dog images. Furthermore, it will showcase any incorrect dog breed assignments, allowing for continuous improvement.

📜 License

This captivating project is licensed under the MIT License. Let your creativity flourish!

🌟 Feel free to check out the project repository and immerse yourself in the fascinating world of dog breed classification! Let's embark on an AI-powered adventure together. 🚀🐾
