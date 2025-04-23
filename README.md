# Hospital Patient Record System

A C++ application to manage hospital patient records, treatment history, and ER queue management.

## Problem Description

This system simulates a hospital's patient management by handling patient information such as name, age, gender, condition, and treatment history. It features a queue system for managing patients in the Emergency Room (ER), and it also includes the ability to treat patients, undo treatments, and search for specific patient records.

## Data Structure Usage

- **Linked List**: Used to manage patient records. Each patient is a node in a linked list.
- **Queue**: Used to manage patients in the ER. The queue ensures that critical patients are treated first.
- **Stack**: Used for undoing the most recent treatment performed on a patient.

## Features

- **Add Patient**: Allows the user to add new patients to the system.
- **View Patients**: Displays all patients in the system.
- **Send to ER**: Moves a patient to the ER with an assigned triage level (Critical, Serious, Stable).
- **Treat ER Patient**: Allows treating patients who are in the ER.
- **Treat Regular Patient**: Allows treating patients who are not in the ER.
- **Undo Last Treatment**: Reverts the most recent treatment added to a patient.
- **Search Patient by Name**: Searches for a patient by their name and displays their information.
- **View ER Queue**: Displays all patients currently in the ER queue.

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/YOUR_USERNAME/Hospital-Patient-Record-System.git

