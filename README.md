# 🧑‍💻 Face-Recognition-Project

![Owner Avatar](https://avatars.githubusercontent.com/u/140405662?v=4)

Welcome to the **Face Recognition Project** — a real-time face recognition solution built with Python, OpenCV, and the face_recognition library.  
Identify faces from live video feeds and images with speed and accuracy.

---

## 🗂️ Repository Structure

```
Face-Recognition-project/
├── 📁 .venv
├── 📁 Age estimation
├── 📄 .gitignore
├── 🖼️ Asit picture.jpg
├── 🖼️ Dheeraj picture.png
├── 📄 Project Synopsis.docx
├── 📄 README.md
├── 🖼️ Sharaddha.jpg
├── 🖼️ Tamanna.jpeg
├── 🎬 Video Demo.mp4
├── 📦 dlib-19.19.0-cp38-cp38-win_amd64.whl
├── 🖼️ face reco.jpg
├── 📄 face.pptx
├── 🐍 face.py
├── 🖼️ shahid.jpg
├── 🖼️ virat.png
```

---

## 🧠 Project Overview

This project provides a Python script for real-time face recognition.  
The script captures video from your camera, detects faces, and matches them against known images.

**Key Features:**
- 🚀 Dynamic Loading: Load any number of facial images for identification.
- 🎥 Real-Time Recognition: Identify faces in live video feeds.
- 👥 Multiple Person Support: Distinguish between multiple known faces.
- 🧑 Age Estimation: (See `Age estimation/` for details.)

---

## ⚙️ Installation Guide (Windows)

### 1️⃣ Install Python

Download and install Python 3.8 (or later) from [python.org](https://www.python.org/).

```bash
python --version
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Install dlib and cmake

Run Command Prompt as administrator, navigate to your project folder, and install the wheel:

```bash
pip install dlib-19.19.0-cp38-cp38-win_amd64.whl
pip install cmake
```

### 4️⃣ Upgrade pip (if necessary)

```bash
pip install --upgrade pip
```

### 5️⃣ Install Face Recognition

```bash
pip install face-recognition
```

### 6️⃣ Install OpenCV

```bash
pip install opencv-python
```

---

## 🏃‍♂️ Running the Project

1. Place all known face images in the project folder.
2. In the script, specify paths to each image and assign names.
3. Run the script:

    ```bash
    python face.py
    ```

4. Press `q` to end the video broadcast.

---

## 🔧 Configuration

- Adjust the `tolerance` parameter in `compare_faces` to improve recognition accuracy.

---

## 🤝 Contributions & Permissions

- We welcome your contributions!  
  Open pull requests and issues to help make this project better.
- For licensing details, see [LICENSE](LICENSE).
- This project is released under the MIT License.

---

## 📬 Contact

Feel free to reach out via [GitHub Issues](https://github.com/Asit-14/Face-Recognition-project/issues) for questions or suggestions.

**Owner:** [Asit-14](https://github.com/Asit-14)

---

Happy coding & stay recognized! 😃
