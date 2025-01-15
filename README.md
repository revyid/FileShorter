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

## 🛠 Installation  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/file-management-script.git
   cd file-management-script
   ```  

2. Run the installer:  
   ```bash
   bash install.sh
   ```  

3. Verify installation by running:  
   ```bash
   file-sorter help
   ```  

---

## 📚 Usage  

### Basic Commands  
- **Help**: Display all available commands.  
  ```bash
  file-sorter help
  ```  

- **Version**: Show script version.  
  ```bash
  file-sorter version
  ```  

- **List Supported Types**: Show all predefined file types and their extensions.  
  ```bash
  file-sorter list
  ```  

- **Directory Stats**: Show statistics about the current directory.  
  ```bash
  file-sorter stats
  ```  

---

### Sorting Commands  
- **Sort by Type** (default):  
  ```bash
  file-sorter
  ```  

- **Sort by Date**:  
  ```bash
  file-sorter date
  ```  

- **Sort by Size**:  
  ```bash
  file-sorter size
  ```  

- **Sort by Extension**:  
  ```bash
  file-sorter extension
  ```  

- **Sort Specific Type**:  
  ```bash
  file-sorter image
  ```  

- **Sort Specific Extension**:  
  ```bash
  file-sorter jpg
  ```  

---

### Management Commands  
- **Add Custom Extension**: Add a new extension to an existing type.  
  ```bash
  file-sorter add {type} {extension}
  ```  
  Example:  
  ```bash
  file-sorter add code jsx
  ```  

- **View History**: Show the last 10 operations (default).  
  ```bash
  file-sorter history
  ```  

- **Simulate Sorting**: Preview the organization process without moving files.  
  ```bash
  file-sorter simulate
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
```  

kalo ada yang kurang atau mau ditambahin, tinggal bilang aja!
