### Create virtual environment

            python -m venv venv

### windows activate environment

            .\venv\Scripts\activate

### Dependencies requirement

            pip install -r requirements.txt

or 

            pip install opencv-python face_recognition cvzone firebase-admin numpy


### delete all files from data folder excluding haarcascade file
### Also delete the attendance.csv from attandance folder


### To add new face data
            python add_faces.py


### To test
            python test.py


### run on streamlit

streamlit run app.py