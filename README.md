# Construction Project Planning Repository

This repository contains key planning documents for a multi-story building construction project. The files are designed to be used together as part of a comprehensive construction management system.

## Files in this Repository

### 1. Raumbuch (Room Book) - `raumbuch.csv`

The Raumbuch is a comprehensive catalog of all spaces in the building, containing detailed specifications for each room including:

- Room identification and location (building ID, floor, room number)
- Physical characteristics (area, height, usage type)
- Material finishes (walls, floors, ceilings)
- Components and installations (doors, windows, lighting, HVAC)
- Equipment and special features
- Fire protection systems
- Special requirements and remarks

This document serves as the definitive reference for all rooms and spaces in the project, ensuring consistent specifications throughout construction.

### 2. Construction Gantt Chart - `construction_gantt_chart.csv`

The Gantt chart provides a detailed construction timeline with:

- 55 key tasks and milestones spanning the entire project
- Task durations and dependencies
- Resource assignments
- Clear organization by construction phase and building area
- Critical path indicators
- Completion tracking

The schedule runs from June 2025 to October 2026 (16 months) and includes all major construction phases:

1. Project Initiation (permits, mobilization)
2. Site Work & Foundation
3. Structural Work (by floor)
4. Building Envelope
5. MEP (Mechanical, Electrical, Plumbing) Installation
6. Interior Construction
7. Finishes
8. Commissioning & Closeout

## How to Use These Files

### Importing the Gantt Chart

The construction_gantt_chart.csv file can be imported into various project management tools:

- **Microsoft Project**: Import as CSV and enable Gantt view
- **Primavera P6**: Import as CSV with task relationships
- **GanttProject**: Direct CSV import 
- **Excel/Google Sheets**: Import and create a timeline view
- **Smartsheet**: Import for collaborative project tracking
- **Monday.com**: Import for visual project management
- **Jira**: Import with the Advanced Roadmaps feature

### Using the Raumbuch

The Raumbuch CSV can be used in several ways:

- **Database Import**: Import into construction management systems 
- **Specification Reference**: Use as authoritative source for all room specifications
- **Quality Control**: Basis for inspection and verification
- **Estimate Validation**: Compare with quantity takeoffs
- **BIM Integration**: Link to Building Information Model rooms

## Project Structure

This project consists of a multi-story building with:

- Basement level (parking, storage, mechanical)
- Ground floor (public areas, reception, services)
- First floor (offices, meeting rooms)
- Second floor (laboratory spaces)
- Third floor (residential apartments)
- Roof level (terrace, mechanical penthouse)

## Contributing to This Repository

When modifying these files, please ensure:

1. All changes to the Raumbuch are coordinated with the design team
2. Schedule updates in the Gantt chart preserve task dependencies
3. Any changes are documented in commit messages

## License

This project is for demonstration purposes only.
