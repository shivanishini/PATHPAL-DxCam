<div align="center">PathPAL DxCam – Digital Microscopy Application
A digital microscopy application developed to connect microscope-based image acquisition with a structured digital workflow for viewing, capturing, and organizing microscopic images.
</div>Project showcase: This repository documents the application through screenshots and project information only. It does not contain the proprietary source code or executable.

📌 Project Overview
PathPAL DxCam is a desktop application developed to support digital microscopy workflows. It provides an interface for connecting to a camera stream, viewing microscopic samples, capturing high-resolution images, and organizing images by case.

The application is part of a broader PathPAL ecosystem that is intended to bring together microscope camera hardware and a web-based platform. The planned deployment and web experience are associated with the official PathPAL website:

Website: https://www.pathpal.in/

The website identifies the PathPAL platform as a pathology-focused AI copilot. The hardware and web-platform rollout should be understood as the broader product direction; this repository's screenshots document the PathPAL DxCam desktop interface.
🔗 System Concept: IoT Camera and Web Application
The broader system is intended to connect an IoT-enabled Raspberry Pi camera (PiCam) attached to a microscope with the PathPAL DxCam web application.

At a high level, the intended workflow is:
1. Microscope imaging: The Raspberry Pi camera captures microscopic samples through the microscope.
2. Camera connectivity: The camera device makes its image stream available over the configured network connection.
3. Application interface: The PathPAL DxCam application is designed to connect to the camera stream using configurable connection details, such as a camera host and port.
4. Image acquisition: Users can view the live microscopic feed and capture images for a case.
5. Web-platform direction: The broader PathPAL platform is intended to provide the web-facing experience for the connected hardware and associated digital workflow through pathpal.in.
The exact production architecture, deployment status, and availability of each hardware-to-web integration component may evolve as the platform is brought live. The screenshots in this repository demonstrate the desktop application's visible interface and features; they should not be taken as proof that every planned web or hardware deployment component is already publicly operational.
✨ Key Features
- Live Microscope Preview: View a live microscopic camera feed within the application when a camera stream is connected.
- Camera Connection Settings: Configure the camera host and port used by the application.
- Connection Status: Display connected and disconnected states in the interface.
- High-Resolution Image Capture: Capture and save microscopic images from the live preview.
- Fullscreen Preview: View the microscopic image in a larger, distraction-reduced preview.
- Case-Based Image Organization: Associate captured images with a case identifier.
- Image Gallery: Review captured image thumbnails through the gallery strip.
- AI Workflow Entry Point: The interface includes an option to upload images for an AI report workflow. The availability and maturity of AI analysis depend on the associated service and deployment.
🖥️ Application Screenshots
The following screenshots are from the PathPAL DxCam desktop application.
1. Main Application Interface
The main screen brings together the case identifier, connection status, image count, preview area, and primary application actions.

2. Live Camera Preview
Example of the application displaying a connected camera feed and captured-image information.

3. Fullscreen Microscopy Preview
A fullscreen view for inspecting a microscopic sample during image review or capture.

4. Camera Connection Settings
The settings interface provides fields for the camera host and port used to connect to the camera stream.

5. Disconnected State
The application interface when a camera stream is not currently connected.

6. Gallery Strip
A view of the image thumbnail strip used to access captured images associated with the current workflow.

7. About PathPAL DxCam
The application's About dialog with its version information and listed capabilities.

🛠️ Technology Stack
Area	Technology
Programming language	Python
Desktop UI framework	PySide6
Image processing and camera handling	OpenCV
Camera hardware direction	Raspberry Pi Camera (PiCam)
Application packaging	PyInstaller
Target desktop platforms	Windows and macOS
Broader product platform	PathPAL website


👩‍💻 Development Contributions
During the internship, I contributed to the development of the PathPAL DxCam desktop application, including:
- Developing the desktop user interface using Python and PySide6.
- Implementing the camera connection settings and connection-status interface.
- Working on live camera preview and microscopic image display.
- Implementing image capture and fullscreen preview workflows.
- Developing case-oriented image organization and gallery functionality.
- Working on packaging and cross-platform application support.
- Contributing to the application workflow intended to fit into the wider IoT-enabled PathPAL ecosystem.
📋 Project Information
- Project: PathPAL DxCam
- Project type: Internship software development project
- Application category: Digital microscopy desktop application
- Hardware direction: IoT-enabled Raspberry Pi camera connected to a microscope
- Web platform: https://www.pathpal.in/
- Focus areas: Desktop application development, camera integration, image acquisition, and digital workflow management
📁 Repository Scope
This repository is a visual and technical project showcase. It contains selected application screenshots and descriptive documentation only.

It intentionally does not include:
- Proprietary application source code
- Compiled application binaries or installers
- Private configuration files, credentials, or API keys
- Patient information or confidential company data
⚖️ Intellectual Property Notice
PathPAL DxCam was developed as part of an internship, and the project and its associated intellectual property are owned by the respective organization. This repository is intended only to describe and showcase the work, subject to the organization's permission to publish the included screenshots and project details.

All product names, platform assets, software, and related intellectual property remain the property of their respective owners. No license or permission to copy, modify, distribute, or commercially use the application is granted by this showcase repository.
<div align="center">Project showcase only — no source code or executable is distributed here.
</div>

**Developed as part of a Software Development Internship.**
