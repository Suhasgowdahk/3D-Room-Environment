# 🏠 3D Room Environment using OpenGL

A **3D Room Simulation Project** built using **OpenGL** and **GLUT** in **C/C++**.  
This project demonstrates fundamental 3D graphics concepts including lighting, camera manipulation, and object rendering.

---

## 🌟 Features

- 🧱 **3D Room Rendering** — includes walls, floor, and ceiling  
- 🪑 **Basic Furniture Models** — tables, chairs, and cupboards  
- 💡 **Lighting Effects** — realistic ambient, diffuse, and specular lighting  
- 🎮 **User Interaction** — toggle lights, adjust camera angle, rotate view  
- 🧭 **Camera Controls** — navigate and explore the room from different perspectives  

---

## 🛠️ Requirements

To run this project, make sure the following are installed:

- **OpenGL**
- **GLUT** (OpenGL Utility Toolkit)
- **C/C++ Compiler** (e.g., GCC, G++)

---

## ⚙️ Installation

### 🧩 Step 1: Install OpenGL and GLUT

**For Debian-based systems (e.g., Ubuntu):**

sudo apt-get install freeglut3-dev
**For Windows:**

Install Code::Blocks or Dev-C++ and configure OpenGL/GLUT libraries manually.

Alternatively, install MSYS2 and use:
pacman -S freeglut

### 🚀 How to Run

**Step 1: Create the Source File**
Create a new file named main.cpp or main.c, and copy the code from your source_code.txt.

**Step 2: Compile the Code**

For C file:
gcc file_name.c -lGL -lGLU -lglut
For C++ file:
g++ file_name.cpp -lGL -lGLU -lglut

**Step 3: Run the Executable**
./a.out
✅ The 3D room environment window should appear.

### 🎮 Controls
Action	Control
Rotate Camera	Mouse Movement
Toggle Lights	Specific Keyboard Keys
Move Camera / Change View	Arrow Keys or Assigned Keys
Exit	ESC key

💡 Tip: Experiment with lighting and camera angles for different visual effects!

#### 🧱 Project Structure
3D-Room-Environment/
│
├── source_code.txt
├── README.md
└── (optional) screenshots/

##📚 Concepts Demonstrated
3D coordinate systems and transformations

Lighting models (ambient, diffuse, specular)

Material properties and reflections

Camera positioning using gluLookAt()

Real-time rendering using GLUT

## 🧠 Learning Outcomes
Hands-on understanding of OpenGL rendering pipeline

Experience with 3D transformations and camera control

Implementing lighting and shading models

Building interactive 3D environments

🧑‍💻 Author
Developed by: Suhas H K
📧 Email: suhashk778@gmail.com

📝 License
This project is open-source and distributed under the MIT License.

