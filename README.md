# Altruisty-Image-Plagarism-checker

The website is a Flask-based image plagiarism detection platform designed to help users verify the originality of images. Users can upload an image through a simple and intuitive interface. Once uploaded, the system preprocesses the image, extracts its features, and compares it against a dataset of original images stored in the system's database.

The application employs advanced algorithms for feature extraction and similarity comparison, ensuring precise results. A dynamic threshold is implemented to filter out low similarity scores, preventing false positives and delivering reliable outcomes. If the uploaded image closely matches any in the dataset, the system flags it as potential plagiarism, displaying the name of the similar image along with the similarity percentage. Otherwise, it confirms no plagiarism detected.

Key features of the website include efficient handling of large datasets, dynamic similarity scoring, and real-time results. The platform ensures the uploaded files are processed securely and are deleted after analysis to maintain user privacy.

This tool is ideal for professionals, educators, and researchers looking to validate the authenticity of images. With its robust backend logic and easy-to-use design, the website serves as a dependable solution for detecting image plagiarism.

### Model Selection and Utilization
Leverage pre-trained models from Hugging Face, such as ResNet, VGG, EfficientNet, or Vision Transformer, for effective feature extraction from images.

### Explaination
This is the initial page where the users upload the file from there database.
![image](https://github.com/user-attachments/assets/f64c1fe0-c83a-486f-a3fa-8f12ba821cd7)

There are two types of Database created Original Database and Modified Database.

Original database: This is the computer's database where if any imagge is uploaded the computer uses this database to compare images to.

Modified Database: This is the user's database where it is used to upload images.
![image](https://github.com/user-attachments/assets/863f34f5-29c7-4c51-89a5-4efbfd6f86d1)

We now upload the images 
![image](https://github.com/user-attachments/assets/7feb2ea1-b4e7-4233-a17c-f6b356f2b380)

Now since we uploaded the image which is already in the Original database folder. The Results would show similarity of a 100%.
The image is being compared to the database of the webiste and results are shown.
![image](https://github.com/user-attachments/assets/cec34d80-d9a7-43b7-8c17-127d65db72cf)

Now uploading a Picture thats not there in the Original Database folder. the Results would show similarity of 0%
![image](https://github.com/user-attachments/assets/c58b8e34-7a08-4256-bc73-d90987f7c309)
![image](https://github.com/user-attachments/assets/eea3afff-dc63-4c6b-b8db-8bc4e5e6bb7e)


## Different types of results:

![image](https://github.com/user-attachments/assets/01f3b13b-7594-461d-a12f-c61327adc275)
![image](https://github.com/user-attachments/assets/fca31379-aaad-4ef2-8198-6eec70740fb6)

![image](https://github.com/user-attachments/assets/cd06a8d0-438b-4dcb-a1d6-7d6a3adf4e54)
![image](https://github.com/user-attachments/assets/9891c078-a24d-45b1-b81e-0583a957f1f2)


### FOR CODE CONTACT: 7358110725
