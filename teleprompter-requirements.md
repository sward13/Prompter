# Teleprompter Web App - Requirements Document

## Overview

A simple, browser-based teleprompter application that allows users to display and scroll through scripts at a customizable pace.

## Target Users

Content creators, presenters, and anyone who needs to read scripts while recording video or presenting.

## Core Features

### 1. Script Input
- Users can paste or type their script into a text input area
- Support for multi-line text content
- Script content persists during the session

### 2. Teleprompter Mode
- Full-screen or maximized display mode for reading
- Clean, distraction-free interface showing only the script
- Easy toggle between edit mode and teleprompter mode
- Exit mechanism (keyboard shortcut or visible control)

### 3. Text Size Control
- Adjustable font size for readability
- Range: Small, Medium, Large, Extra Large (or slider control)
- Changes apply in real-time
- Settings persist during the session

### 4. Scroll Speed Control
- Adjustable auto-scroll speed
- Pause/resume functionality
- Manual scroll override capability
- Speed range: Very Slow to Very Fast (or slider control)
- Settings persist during the session

## Technical Requirements

### Platform
- Web-based application
- Runs entirely in the browser (client-side)
- No backend server required
- Responsive design (works on tablets and desktops)
- Compatible with modern browsers (Chrome, Firefox, Safari, Edge)

### Technology Stack
- HTML5
- CSS3
- JavaScript (vanilla or lightweight framework)

## User Interface Requirements

### Edit Mode
- Text input area (textarea or contenteditable)
- Controls for text size selection
- Controls for scroll speed selection
- "Start Teleprompter" button

### Teleprompter Mode
- Full viewport display
- Centered, readable text
- Scroll speed controls (visible or keyboard-accessible)
- Pause/play control
- Exit control

## Keyboard Controls (Suggested)

- **Spacebar**: Pause/resume scrolling
- **Escape**: Exit teleprompter mode
- **Arrow Up/Down**: Adjust scroll speed
- **+/-**: Adjust text size

## Non-Functional Requirements

- Fast load time
- Smooth scrolling performance
- Responsive design (works on tablets and desktops)
- Intuitive, minimal learning curve

## Out of Scope (Phase 1)

- Script saving/loading
- Multiple script management
- User accounts
- Cloud storage
- Mirroring/flipping text
- Rich text formatting
- Collaboration features

## Success Criteria

- Users can quickly paste a script and start reading within seconds
- Smooth, distraction-free reading experience
- Intuitive controls that don't interrupt the flow
- Works reliably across major browsers
