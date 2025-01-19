# Altruisty-Image-Plagarism-checker
The website is a Flask-based image plagiarism detection platform designed to help users verify the originality of images. Users can upload an image through a simple and intuitive interface. Once uploaded, the system preprocesses the image, extracts its features, and compares it against a dataset of original images stored in the system's database.

The application employs advanced algorithms for feature extraction and similarity comparison, ensuring precise results. A dynamic threshold is implemented to filter out low similarity scores, preventing false positives and delivering reliable outcomes. If the uploaded image closely matches any in the dataset, the system flags it as potential plagiarism, displaying the name of the similar image along with the similarity percentage. Otherwise, it confirms no plagiarism detected.

Key features of the website include efficient handling of large datasets, dynamic similarity scoring, and real-time results. The platform ensures the uploaded files are processed securely and are deleted after analysis to maintain user privacy.

This tool is ideal for professionals, educators, and researchers looking to validate the authenticity of images. With its robust backend logic and easy-to-use design, the website serves as a dependable solution for detecting image plagiarism.

![image](https://github.com/user-attachments/assets/f64c1fe0-c83a-486f-a3fa-8f12ba821cd7)
This is the initial page where the users upload the file from there database.

There are two types of Database created Original Database and Modified Database.
Original database: This is the computer's database where if any imagge is uploaded the computer uses this database to compare images to.
Modified Database: This is the user's database where it is used to upload images.
![image](https://github.com/user-attachments/assets/863f34f5-29c7-4c51-89a5-4efbfd6f86d1)

