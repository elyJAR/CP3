# Classroom Presenter 3 (CP3)

Classroom Presenter is a Tablet PC-based presentation and interaction system that supports the sharing of digital ink on slides between instructors and students. When used as a presentation tool, Classroom Presenter integrates digital ink and slides, combining the advantages of whiteboard-style lecturing with slide-based presentations. 

Connecting instructor and student devices creates additional feedback channels and active learning opportunities in the classroom.

![Classroom Presenter Screenshot](Miscellaneous/cp3screenshot.JPG)

---

## Key Features

* **Digital Ink Annotation**: Instructors and students can draw over slides with vector digital ink overlays in real-time.
* **Dual Monitor Support**: Present slides on a projector screen without exposing presenter controls or personal notes.
* **Student Submissions**: Allows students to solve slide problems and submit them to the instructor for real-time lecture showcase.
* **Quick Polling**: Instructors can initiate surveys (e.g., Multiple Choice A/B/C/D, Yes/No) and gather aggregated client/web results.
* **Cross-Platform Browser Client**: A built-in web server allows students to participate via mobile/desktop browsers without needing the desktop app.
* **Flexible Networking**: Communicates using TCP/IP connections or multicast RTP/ConferenceXP services.

---

## Technology Stack

* **Core**: C# (.NET Framework 4.0/3.5, historically built using Visual Studio 2010).
* **UI**: Windows Forms (WinForms) for the desktop client, with GDI+ rendering.
* **Web Services**: Wrapper for the high-performance C++ mongoose web server to host client-side assets and bind dynamic API routes.
* **Client Web App**: HTML5, Vanilla CSS, and JavaScript.

---

## Getting Started

### Building the Project
Classroom Presenter 3 recommends **Visual Studio 2010** or newer with .NET SDKs.
1. Open [Presenter.sln](Presenter.sln).
2. Build the solution.

### Usage
Start Classroom Presenter with command-line arguments:
* `--input <file>`: Open a PPT, PPTX, XPS, or native CP3 file.
* `--standalone`: Start in disconnected instructor mode.

---

## License
Classroom Presenter is licensed under the **Apache License v 2.0**.

---

## Related Projects
* [ConferenceXP](http://github.com/conferencexp/conferencexp)
* [CXP Archive Transcoder](http://github.com/fvideon/archivetranscoder)
* [CXP Windows Media Gateway](http://github.com/fvideon/wmgateway)
* [CXP WebViewer](http://github.com/fvideon/webviewer)
