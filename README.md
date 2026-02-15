# 🎓 University Research Facility Access Control System

## 📋 Project Overview
This project implements a **forward-chaining Knowledge-Based System (KBS)** to automate access permissions for a restricted university research facility. The system processes credentials, safety certifications, and health screenings to determine specific entry levels.

## 🚀 How to Run
1. Ensure Python 3.x and Jupyter Notebook are installed.
2. Open `kbs_quiz.ipynb`.
3. Fill in your Name and Registration Number in the top cell.
4. Execute all cells (**Cell > Run All**).
5. Review the terminal-style output for the inference process.

## 📚 System Logic

### Base Facts
- `security_badge_issued_2025`: Valid ID for the current year.
- `research_personnel_status`: Confirms status as staff or faculty.
- `safety_training_completed`: Validates lab safety compliance.
- `temperature_screening_passed`: Basic health check.
- `equipment_certification_active`: Specialized certification for lab tools.
- `visitor_log_signed`: Formal registration for non-staff.

### Key Rules
1. **Identity & Safety**: Single conditions to confirm badge and training validity.
2. **Authorization**: Multi-condition rules combining personnel status with certifications.
3. **Inference Chaining**: Logic that links building entry permission to specific lab access.
4. **Final Decision**: An "OR" logic rule that grants campus entry to either verified researchers or screened visitors.

## ⚙️ Project Structure
- `kbs_quiz.ipynb`: The core Python implementation containing the `InferenceEngine` class and rule definitions.
- `README.md`: System documentation and setup instructions.

## 👤 Student Information
- **Name:** [Your Full Name]
- **Registration Number:** [Your Registration Number]
- **Course:** Introduction to Knowledge-Based Systems