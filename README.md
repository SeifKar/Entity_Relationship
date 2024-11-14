# Gym Management System - Entity Relationship Model

This repository contains the Entity-Relationship (ER) model for a comprehensive gym management system. The system is designed to handle multiple gymnasiums, member registrations, session management, and coach assignments.

## System Requirements

### Gymnasium
- Each gymnasium has a unique identifier, name, address, and telephone number
- Can register multiple members
- Hosts multiple sessions

### Members
- Identified by unique identifier
- Personal information includes: last name, first name, address, date of birth, and gender
- Can register at one gymnasium
- Can attend multiple sessions

### Sessions
- Characterized by sport type and schedule
- Maximum capacity of 20 members per session
- Belongs to a specific gymnasium
- Can be led by up to 2 coaches

### Coaches
- Personal information includes: last name, first name, age, and specialty
- Can lead multiple sessions

## ER Diagram
The ER diagram is created using PlantUML. To view the diagram, you can use:
- Online PlantUML editor
- Local PlantUML installation
- VS Code with PlantUML extension

## Files
- `gym_er_model.puml`: Contains the PlantUML code for the ER diagram
- `README.md`: Project documentation

## Use Case
This model was designed to solve a real-world problem where a large gym chain needed to transition from a manual card-based system to a digital solution for managing their operations more efficiently.
