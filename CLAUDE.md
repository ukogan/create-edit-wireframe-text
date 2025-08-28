# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an editable wireframe system for FreeBusy, a calendar availability application. The project consists of interactive HTML wireframes with real-time text editing capabilities for prototyping UI text content and layouts.

## Architecture

**Frontend-Only Structure:**
- Self-contained HTML wireframes with embedded CSS and JavaScript
- JSON configuration files store text content separately from presentation
- Real-time text editor panel allows live editing of wireframe content
- No build system or server dependencies - pure client-side implementation

**Key Components:**
- `main-window-wireframe.html` - Main application interface wireframe
- `onboarding-wireframe.html` - User onboarding flow wireframe  
- `settings-wireframe.html` - Settings/configuration interface wireframe
- `FreeBusy Main Window - Editable Wireframe2.html` - Alternative main window version
- `freebusy-main-window-2025-08-27.json` - Text content configuration for main window
- `freebusy-onboarding-2025-08-27.json` - Text content configuration for onboarding

**Wireframe System Features:**
- Side-by-side text editor and wireframe preview
- Live text updates reflected immediately in wireframe
- JSON export/import functionality for content management
- Responsive design with sticky editor panel
- Copy-to-clipboard and save-to-file functionality

## File Structure

**HTML Wireframes:**
- Each wireframe is a standalone HTML file with embedded CSS and JavaScript
- Text content is dynamically populated from JavaScript objects or JSON imports
- Editor panel allows real-time modification of all text elements

**JSON Configuration:**
- Separate JSON files store text content with semantic keys
- Format includes metadata (exportDate, wireframeType, version) and textContent object
- Text keys correspond to DOM elements that can be edited

## Usage

**Viewing Wireframes:**
- Open any HTML file directly in a web browser
- No server or build process required
- Editor panel on left, wireframe preview on right

**Editing Content:**
- Use the text editor panel to modify any displayed text
- Changes appear immediately in the wireframe
- Export updated content as JSON for persistence

**Content Management:**
- JSON files can be imported to populate wireframe text
- Export functionality saves current text state to downloadable JSON
- Version tracking included in JSON metadata