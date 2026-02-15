<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

---

<p align="center">
  <strong>Software Engineering</strong>
</p>

<h1 align="center">
  Preze Cinemas Desktop - Phase 1<br>
  Use Case Analysis
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

---

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Georgios Prezerakos, Professor
</p>

<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/george-prezerakos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/georgenprezerakos/" target="_blank">LinkedIn</a>
</p>

---

<p align="center">
  Athens, May 2023
</p>

---

# Preze Cinemas Desktop - Phase 1: Use Cases

This repository contains **Phase 1** of the *Preze Cinemas Desktop* project, developed for the **Software Engineering** course.

The goal of the project is to design a **cinema ticket reservation system** that enables customers to browse movies, reserve tickets, and complete secure payments while allowing cinema operators to manage screenings and availability.

Phase 1 focuses on **system analysis and requirements modeling** through **Use Case Diagrams**.

---

## Table of Contents

| Section | Folder/File | Description |
|------:|-------------|-------------|
| 1 | `assign/` | Assignment instructions and course material |
| 1.1 | `assign/seng_instructions_2022_23_v2.pdf` | Assignment instructions (English) |
| 1.2 | `assign/λμηχ_οδηγίες_2022_23_β2.pdf` | Assignment instructions (Greek) |
| 2 | `diagrams/` | Use case diagrams in image and editable formats |
| 2.1 | `diagrams/cinemaUseCases.png` | Use case diagram (English image) |
| 2.2 | `diagrams/cinemaUseCases.vsdx` | Use case diagram (English editable) |
| 2.3 | `diagrams/σίνεμαΣεναρίωνΧρήσης.png` | Use case diagram (Greek image) |
| 2.4 | `diagrams/σίνεμαΣεναρίωνΧρήσης.vsdx` | Use case diagram (Greek editable) |
| 3 | `docs/` | Exported documentation |
| 3.1 | `docs/Use-Cases-Diagram.pdf` | Use case documentation (English) |
| 3.2 | `docs/Διάγραμμα-Σεναρίων-Χρήσης.pdf` | Use case documentation (Greek) |
| 4 | `README.md` | Project overview |

---

## Project Overview

The application supports cinema customers in:

- Browsing available movies
- Selecting showtimes and screening rooms
- Reserving seats and tickets
- Completing secure payments
- Receiving digital ticket confirmations

This phase defines **how users interact with the system**, forming the basis for future implementation phases.

---

## Phase 1 Objective – Use Case Analysis

The first development phase identifies:

- System actors
- System services
- User interaction flows
- External system interactions

All interactions are modeled using UML Use Case diagrams.

---

## System Actors

### Customer
Represents all end users of the system:

- New customers registering accounts
- Existing customers logging in
- Customers booking movie tickets

### Bank System
An external system responsible for:

- Payment validation
- Account balance verification
- Transaction confirmation

---

## Core Functionalities

### Account Management
Customers can:

- Register with personal information
- Log in securely using credentials
- Manage access to reservations

### Reservation Process
Users are able to:

- Select movies
- Choose available showtimes
- Select rooms and available seats
- Reserve tickets for screenings

### Optional Viewing Features
Enhanced viewing options may include:

- Dolby Atmos sound
- 3D movie projection

### Payment & Verification
Payments are processed through the external Bank System, including:

- Balance validation
- Transaction approval or rejection

### Post-Purchase Services
After successful booking, users may:

- Obtain proof of transaction
- Download or store digital tickets

---

## System Logic Modeling

The use case model applies UML relationships to organize behavior.

### Include Relationships
Mandatory sub-processes, such as:

- Login including credential verification.

### Extend Relationships
Conditional processes, such as:

- Displaying error messages
- Applying promotional discounts
- Handling exceptional scenarios

---

## Conclusion

Phase 1 establishes the functional interaction model of **Preze Cinemas Desktop**, serving as the foundation for future design and implementation phases. The system aims to provide a user-friendly cinema reservation experience while ensuring secure transaction handling and structured reservation management.