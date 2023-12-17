# Software Requirements Specification

## Introduction

### Purpose

This Software Requirements Specification (SRS) document provides a detailed description of the functionality and requirements for developing an embedded map for the city library.

## Document Conventions

- HTML: HyperText Markup Language
- CSS: Cascading Style Sheets
- JS: JavaScript
- SVG: Scalable Vector Graphics
- WebStorm: Integrated Development Environment from JetBrains

## Intended Audience and Reading Suggestions

This document is intended for developers, designers, and anyone interested in creating an embedded map for the city library.

## Project Scope

The project involves the development of a multi-layered map integrated into the library's website, with the ability to add historical markers and group objects.

## References

- [SVG Specification](https://www.w3.org/Graphics/SVG/)
- [WebStorm Documentation](https://www.jetbrains.com/webstorm/documentation/)

## Overall Description

### Product Perspective

The developed map is an embedded module for the library's website, providing users with interactive access to historical objects.

### Product Features

1. Embedded multi-layered map
2. Addition of markers with information
3. Grouping of objects
4. Interactive interaction with the map

### User Documentation

User documentation explaining the interaction with the map and available features is required.

### Assumptions and Dependencies

- Use WebStorm for development
- Optimize the map for embedding in the library's website

## System Features

### System Feature 1: Historical Markers

#### Description and Priority

Adding markers with designations of historical objects.

#### Stimulus/Response Sequences

- **Stimulus:** User selects "Add Marker."
- **Response:** Popup window with the ability to enter information about the marker.

#### Functional Requirements

- Markers must be categorized.
- Ability to display/hide groups of markers.

### System Feature 2: Interactive Map

#### Description and Priority

Development of an interactive multi-layered map.

#### Stimulus/Response Sequences

- **Stimulus:** User hovers over a marker.
- **Response:** Brief information about the marker is displayed.

#### Functional Requirements

- Use HTML, CSS, JS to implement the map.
- Use SVG as the base for the map.

## External Interface Requirements

### User Interfaces

The interface should be intuitive and attractive to users.

### Software Interfaces

Use WebStorm for development.

### Hardware Interfaces

No specific hardware requirements.

### Communication Interfaces

The map should be embedded in the library's webpage.

## Non-functional Requirements

### Performance Requirements

- The map should be optimized and not cause delays in page loading.

### Software Quality Attributes

- Code must be easily readable and maintainable.
- Use unit tests to check components.

### Security Requirements

Develop the map as a separate module for security and to avoid conflicts with the library's system.

## Appendix A: Glossary

- HTML: HyperText Markup Language.
- CSS: Cascading Style Sheets.
- JS: JavaScript programming language.
- SVG: Scalable Vector Graphics.
- WebStorm: Integrated Development Environment from JetBrains.

## Appendix B: Analysis Models

Currently, no specific analytical models and diagrams are defined for this project. This document serves as a plan for future development, and types of analytical models will be determined in later stages of the project.

## Appendix C: Issues List

At present, specific issues or tasks have not been identified. This section remains open for recording potential questions, issues, or tasks that may arise during development. Issues will be added as they are identified and project requirements emerge.
