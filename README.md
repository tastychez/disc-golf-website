# Disc Golf Disc Cleaner Website

This repository contains the project showcase website for the **Disc Golf Disc Cleaner**, an automated robotic system designed to clean disc golf discs using AI-powered dirt detection. The website provides a comprehensive overview of the project, including system design, development process, team information, and technical documentation.

**Project Codebase:** [https://github.com/ConnorHoang/Disk-Golf-Cleaner](https://github.com/ConnorHoang/Disk-Golf-Cleaner)

## About the Project

The Disc Golf Disc Cleaner is a fully automated cleaning station that combines intelligent sensing, precision mechanics, and computer vision to deliver a complete cleaning solution for disc golf discs. The system integrates:

- **AI-Powered Dirt Detection** - Custom machine learning model using Roboflow to detect dirt and debris on disc surfaces
- **Automated Disc Handling** - Rotary encoder-based load sensing detects disc presence and monitors chuck motor RPM for secure clamping
- **Precision Cleaning** - Servo-actuated brush assembly scrubs the disc surface during rotation
- **State Machine Control** - Python-based control system orchestrates the entire cleaning process through distinct operational states
- **User Interface** - LCD display provides real-time status updates and clear instructions

The project was developed as part of Olin College's Principles of Integrated Engineering (PIE) course, demonstrating the integration of mechanical, electrical, and software systems in a complete mechatronic solution.

## Website Features

This website showcases the complete project through several comprehensive sections:

### Home Page
- Project overview and objectives
- Feature highlights with implementation status
- Gallery of project photos
- Demo video and CAD animations

### System Design
- Complete system architecture diagrams
- Data and energy flow visualizations
- Detailed design documentation for:
  - Enclosure design (dual-enclosure system)
  - 3-jaw chuck mechanism
  - Brush assembly with gear train
  - Grate assembly with structural analysis
  - Electrical design and wiring diagrams
  - Software architecture and control logic

### Development Process
- Three-sprint development timeline:
  - **Sprint 1:** Ideation and concept development
  - **Sprint 2:** Prototyping and subsystem development
  - **Sprint 3:** Integration and MVP delivery

### Team & Reflections
- Team member profiles with learning goals
- Individual reflections on the project experience
- Cross-disciplinary collaboration insights

### Documentation
- Mechanical build photos
- Design sketches and ideation
- Wiring and electrical documentation
- CAD renderings and animations

### Additional Resources
- Bill of Materials (BOM) with cost breakdown
- Key learnings and lessons from the project
- Technical specifications and dependencies

## Tech Stack

- **React** - UI framework for building interactive components
- **Vite** - Fast build tool and development server
- **React Router** - Client-side routing with hash-based navigation
- **Tailwind CSS** - Utility-first CSS framework for styling
- **Three.js / React Three Fiber** - 3D graphics library for the animated disc scene on the homepage
- **PostCSS** - CSS processing with autoprefixer

## Related Resources

- **Roboflow Workflow:** [View ML Pipeline](https://app.roboflow.com/workflows/embed/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ3b3JrZmxvd0lkIjoiZ2k0azZzeDFscWxwc1J1ZVd1YkIiLCJ3b3Jrc3BhY2VJZCI6IlFrWWFXQmI5NzNQWTNLN2pkYnlhVlBFMVV6eTIiLCJ1c2VySWQiOiJRa1lhV0JiOTczUFkzSzdqZGJ5YVZQRTFVenkyIiwiaWF0IjoxNzY2MDQ1MzY0fQ.kjzo9iuPqUFK4MCBv9G_rBWBhPuV9UrvZTv3FDnYCrU)
