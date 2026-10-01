\# 🤟 Sign Language to Text \& Speech



A real-time \*\*Sign Language Recognition System\*\* that uses Computer Vision and a Convolutional Neural Network (CNN) to recognize hand gestures and convert them into \*\*text and speech\*\*.



The system captures hand gestures through a webcam, processes the image, predicts the corresponding sign using a trained CNN model, and converts the recognized output into speech.



\---



\## 🚀 Features



\- 🤟 Real-time sign language recognition

\- 📷 Webcam-based hand gesture detection

\- 🧠 CNN-based gesture classification

\- 🔤 Sign language to text conversion

\- 🔊 Text-to-speech output

\- ⚡ Real-time prediction

\- 🖥️ Desktop GUI interface

\- 💾 Pre-trained CNN model included



\---



\## 🛠️ Technologies Used



| Technology | Purpose |

|---|---|

| Python | Core programming language |

| TensorFlow | Deep learning framework |

| Keras | CNN model implementation |

| OpenCV | Image processing and webcam handling |

| MediaPipe / CVZone | Hand detection and tracking |

| NumPy | Numerical operations |

| Tkinter | Graphical user interface |

| pyttsx3 | Text-to-speech conversion |



\---



\## 🧠 System Workflow



```text

Webcam

&#x20;  ↓

Hand Detection

&#x20;  ↓

Image Preprocessing

&#x20;  ↓

CNN Model

&#x20;  ↓

Gesture Classification

&#x20;  ↓

Recognized Character

&#x20;  ↓

Text Formation

&#x20;  ↓

Text-to-Speech


📂 Project Structure

sign-language-to-text/

│

├── final\_pred.py

├── prediction\_wo\_gui.py

├── data\_collection\_binary.py

├── data\_collection\_final.py

│

├── cnn8grps\_rad1\_model.h5

├── hand\_landmarker.task

├── white.jpg

│

├── requirements.txt

├── README.md

├── .gitignore

│

└── AtoZ\_3.1/

&#x20;   └── Dataset



Note: The AtoZ\_3.1 dataset is excluded from the GitHub repository to keep the repository lightweight.



⚙️ Installation

1\. Clone the repository

git clone https://github.com/Omkar-1710/sign-language-to-text.git

2\. Open the project directory

cd sign-language-to-text

3\. Create a virtual environment



For the recommended Python environment:



py -3.10 -m venv venv

4\. Activate the virtual environment



Windows:



venv\\Scripts\\activate

5\. Install dependencies

pip install tensorflow==2.10.0

pip install numpy==1.23.5

pip install opencv-python

pip install pillow

pip install cvzone

pip install mediapipe

pip install pyttsx3

pip install pyenchant

pip install matplotlib

▶️ Run the Project



After activating the virtual environment:



python final\_pred.py



Allow the application to access your webcam.



The system will detect hand gestures and predict the corresponding sign.



🧠 Machine Learning Model



The project uses a Convolutional Neural Network (CNN) trained for hand gesture classification.



The trained model is provided as:



cnn8grps\_rad1\_model.h5



The model performs image-based classification of hand gestures and provides the predicted character to the application.



📸 Screenshots



Screenshots of the running application can be added here.



Example:



!\[Application Screenshot](screenshots/demo.png)

🎯 Applications



This project can be used as a foundation for:



Accessibility tools

Communication assistance

Sign language learning

Human-computer interaction

Educational applications

Assistive technology

🔮 Future Improvements

Support for complete words and sentences

Recognition of dynamic gestures

Improved accuracy using larger datasets

Support for multiple sign languages

Web-based interface

Mobile application

Cloud-based deployment

Improved natural language processing

Continuous sentence prediction

⚠️ Limitations

Recognition performance depends on lighting and camera quality.

The current system focuses primarily on trained/static hand gestures.

The available model supports the gesture classes on which it was trained.

Dataset expansion can improve generalization.

👨‍💻 Author



Omkar Wankar



AI \& Data Science | Machine Learning | Data Analytics



GitHub:

https://github.com/Omkar-1710



⭐ Project



If you find this project useful, consider giving the repository a ⭐ on GitHub.





\### 2. Save it



In Notepad:



\*\*File → Save\*\*



Then close Notepad.



\### 3. Add it to Git



In your CMD:



```cmd

git add README.md



Then:



git commit -m "Add professional README"



Then:



git push

4\. Verify



Open your repository:



Sign Language to Text — GitHub



GitHub should now automatically display the README on the repository homepage.



One correction before you push



In the README above, I included the dataset in the example project structure but also said it's excluded. Since it's actually excluded from GitHub, I'd make that section cleaner by showing:



sign-language-to-text/

│

├── final\_pred.py

├── prediction\_wo\_gui.py

├── data\_collection\_binary.py

├── data\_collection\_final.py

├── cnn8grps\_rad1\_model.h5

├── hand\_landmarker.task

├── white.jpg

├── requirements.txt

├── README.md

└── .gitignore



Use this version for the project structure.

