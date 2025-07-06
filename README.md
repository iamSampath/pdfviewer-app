# PDF Viewer App

A lightweight, standalone **PDF viewer** built in **JavaFX**, designed for smooth viewing, searching, and managing PDF files without the need for any external dependencies like Adobe Reader. This app supports highlighting text, zooming, exporting pages, and printing — all with a clean, simple interface.

## 🚀 Features

- **🧭 Open and View PDFs**: Simple PDF viewing capabilities.
- **🔍 Search**: Find any text inside the document with ease.
- **🎯 Highlight Text**: Select and highlight specific words or phrases in the document.
- **🖨 Print**: Print the current page of the PDF.
- **📸 Export Page as Image**: Export the current page as an image for easy sharing.
- **🔄 Zoom**: Zoom in and out of pages to fit your viewing needs.
- **📦 Standalone**: No need for an external PDF viewer or Java installation — the app includes all necessary components.

## 💻 Installation

### Download the Installer

You can download the Windows installer from the latest release:

- [**Download PDF Viewer v1.0**](https://github.com/iamSampath/pdfviewer-app/archive/refs/tags/V1.0.zip)

Once downloaded, extract the `.zip` file and run the **`PdfViewerApp-1.0.exe`** installer.

### Windows Installation

1. **Run the installer**: After downloading and extracting the `.zip` file, double-click the `PdfViewerApp-1.0.exe` file to start the installation.
2. **Follow the prompts**: The installer will guide you through the setup process. 
3. **Launch the App**: After installation, you can open the app directly from your Start Menu or desktop shortcut.

### macOS (Coming Soon)

We're currently working on a macOS version. Stay tuned for future updates.

---

## 🛠️ Development Setup

### Prerequisites

Before running or building the app locally, ensure that you have the following installed:

- **Java JDK 21 or higher**: [Download Java 21](https://adoptopenjdk.net/)
- **Maven**: [Install Maven](https://maven.apache.org/install.html)
- **JavaFX SDK**: [Download JavaFX SDK](https://gluonhq.com/products/javafx/)

### Running Locally

Clone the repository:

```bash
git clone https://github.com/iamSampath/pdfviewer-app.git
cd pdfviewer-app

```

Build the project:

```bash
  mvn clean package
```
Run the application locally (with a running JavaFX-enabled JDK):

```bash
 java -jar target/PdfViewerApp-1.0.jar
```
##👨‍💻 Contributing

We welcome contributions! If you have an idea for a new feature or find a bug, feel free to open an issue or submit a pull request.

Steps to Contribute:
1. Fork the repository.
2. Create a feature branch (git checkout -b feature-name).
3. Commit your changes (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-name).
5. Create a new pull request.

##📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

🔗 Links
GitHub Repository: https://github.com/iamSampath/pdfviewer-app
Release Notes: https://github.com/iamSampath/pdfviewer-app/releases

```yaml

### Key Updates:
- The **"Build the Project"** section is now included under **Development Setup** to guide developers who want to clone the repository, build, and run the project locally.
This version will ensure that contributors know how to **set up and build the project** while users can easily download the installer.

```

