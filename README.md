# File Management Script  

**Version:** 2.0.0  
**Author:** File Management Script  
**Year:** 2025  

## 📋 Description  
The **File Management Script** is a simple and efficient tool for organizing files in a directory based on **type**, **extension**, **size**, or **date**. It supports a wide range of file types such as images, videos, documents, code, archives, and more.  

This script is perfect for:  
- Organizing cluttered files in your Downloads folder.  
- Automatically moving files into categorized folders.  
- Sorting files based on your preferences (size, type, or others).  

---

## 🚀 Features  
- **Type-based Sorting**: Categorizes files into predefined folders (e.g., images, videos, documents).  
- **Date-based Sorting**: Organizes files into folders by creation date (e.g., `YYYY/MM/DD`).  
- **Size-based Sorting**: Groups files into `small`, `medium`, and `large` categories.  
- **Extension-based Sorting**: Creates folders for each file extension (e.g., `.jpg`, `.pdf`).  
- **Custom Extensions**: Add your own extensions to existing file types.  
- **Exclusion List**: Skip specific files or folders during the sorting process.  
- **Simulation Mode**: Preview the organization process without moving files.  

---

## 🚀 Installation  

1. **Download the script**    
   ```bash
   git clone https://github.com/revylab/FileShorter.git
   ```
   or
   <a href="https://github.com/revylab/FileShorter/releases">Release</a>

3. **Navigate to the project directory**  
   ```bash
   cd FileShorter
   ```

4. **Make the script executable**  
   ```bash
   chmod +x install
   ```

5. **Run the installer**  
   ```bash
   ./install
   ```

6. **Verify installation**  
   Ensure the `rfile` command is available by checking:  
   ```bash
   which rfile
   ```
   or
   ```bash
   rfile help
   ```

---

## 📚 Usage  

### Basic Commands  
- **Help**: Display all available commands.  
  ```bash
  rfile help
  ```  

- **Version**: Show script version.  
  ```bash
  rfile version
  ```  

- **List Supported Types**: Show all predefined file types and their extensions.  
  ```bash
  rfile list
  ```  

- **Directory Stats**: Show statistics about the current directory.  
  ```bash
  rfile stats
  ```  

---

### Sorting Commands  
- **Sort by Type** (default):  
  ```bash
  rfile
  ```  

- **Sort by Date**:  
  ```bash
  rfile date
  ```  

- **Sort by Size**:  
  ```bash
  rfile size
  ```  

- **Sort by Extension**:  
  ```bash
  rfile extension
  ```  

- **Sort Specific Type**:  
  ```bash
  rfile image
  ```  

- **Sort Specific Extension**:  
  ```bash
  rfile jpg
  ```  

---

### Management Commands  
- **Add Custom Extension**: Add a new extension to an existing type.  
  ```bash
  rfile add {type} {extension}
  ```  
  Example:  
  ```bash
  rfile add code jsx
  ```  

- **View History**: Show the last 10 operations (default).  
  ```bash
  rfile history
  ```  

- **Simulate Sorting**: Preview the organization process without moving files.  
  ```bash
  rfile simulate
  ```  

---

## 📦 Example  

### Before Sorting:  
```plaintext
Downloads/
├── image1.jpg
├── video1.mp4
├── document.pdf
├── script.sh
├── random_file.txt
```  

### After Sorting (Type-Based):  
```plaintext
Downloads/
├── images/
│   └── image1.jpg
├── videos/
│   └── video1.mp4
├── documents/
│   └── document.pdf
├── scripts/
│   └── script.sh
├── text/
│   └── random_file.txt
```  

---

## ⚠️ Notes  
- Ensure you have the required permissions to move files in the target directory.  
- Use the `simulate` command to preview changes before execution.  

---

## 📜 License  
This project is licensed under the MIT License.  

---

## 🤝 Contribution  
Feel free to submit issues or pull requests to improve this script!  

---

## 💡 Inspiration  
This script was created to simplify file organization and reduce manual sorting efforts.  
