## **3D Solar System Visualization**

This project creates an interactive 3D solar system model using **HTML**, **CSS**, and **JavaScript**. It allows users to toggle between different views (2D/3D), zoom in/out, adjust speed, and change the size and distance of objects in the solar system. The solar system’s elements are dynamically styled based on screen size for responsiveness.

---

### **Features**
- **Interactive Solar System**: Toggle between 2D and 3D views.
- **Responsive Design**: Adapts to various screen sizes with adjustable font and element sizes.
- **Dynamic Controls**: Adjust speed, size, and distance of objects.
- **Smooth Transitions**: Custom animations for a seamless user experience.

---

### **Technologies Used**
- **HTML**
- **CSS** (with SCSS)
- **JavaScript** (jQuery)

---

### **How to Run the Project**

#### **1. Clone the Repository**
   If you haven't already, clone the repository to your local machine:

   ```bash
  git clone https://github.com/HimKasera/Solar-System-3D.git
   ```

#### **2. Set Up Your Local Environment**
   This project can be run entirely in the browser. However, if you want to work with **SCSS** files, you need to compile them into **CSS**.

   **To compile SCSS (Optional):**
   - Install [Node.js](https://nodejs.org/) if you haven't already.
   - Install [Sass](https://sass-lang.com/) globally using npm:

     ```bash
     npm install -g sass
     ```

   - Navigate to the directory containing your SCSS files and run:

     ```bash
     sass style.scss style.css
     ```

     This will compile `style.scss` into `style.css`.

#### **3. Open the HTML File in a Browser**
   - Simply open the `index.html` file in any modern web browser (Google Chrome, Firefox, Edge, etc.) by double-clicking the file or right-clicking and selecting **Open with** → **Your Browser**.

#### **4. Use the Project**
   - Once the project is loaded, you can interact with the 3D solar system by clicking on various controls to toggle views, zoom in/out, adjust speed, and manipulate the objects in the solar system.

#### **5. (Optional) Serve Locally Using a Local Server**
   If you want to serve the files over a local server (especially useful if you use AJAX or dynamic content), you can use one of the following methods:

   - **Using Python (if you have Python installed):**

     For Python 3.x:
     ```bash
     python -m http.server
     ```

     This will start a local server at `http://localhost:8000`.

   - **Using VS Code Live Server Extension:**
     If you use Visual Studio Code, install the **Live Server** extension and simply click **Go Live** in the bottom-right corner of VS Code to open your project in the browser.

#### **6. Enjoy the Project!**
   After following these steps, you should be able to see and interact with the 3D solar system.
