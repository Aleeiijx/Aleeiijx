# VOTE - Virtual Online Transparent Elections

[![Java](https://img.shields.io/badge/Java-Programming-orange)](https://www.oracle.com/java/)  
[![SDG 16](https://img.shields.io/badge/SDG-16-blue)](https://sdgs.un.org/goals/goal16)  
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](https://github.com/yourusername/voting-system)

---

## Project Overview
The **VOTE - Virtual Online Transparent Elections** is a Java-based application that facilitates democratic participation through a simple yet effective platform. Users can register as voters, cast their votes, and participate in elections, while administrators can manage elections, view results, and oversee the electoral process. 

The system's architecture adheres to Object-Oriented Programming (OOP) principles, ensuring modularity, maintainability, and extensibility for future enhancements.

---

## Features
### For Voters:
- **Sign Up**: Register as a voter by providing ID, name, and age (must be 18 or older).  
- **Sign In**: Log in to view the list of candidates and cast your vote.
- **Vote**: Securely vote for your preferred candidate in an election.

### For Admins:
- **Admin Login**: Access admin privileges using a secure login system.  
- **Create Elections**: Add new elections and register candidates.  
- **View Results**: Display election results with real-time vote counts.  
- **Election Stories**: View activity logs (e.g., voter participation and election events).  

---

## OOP Principles Applied
The Voting System leverages core OOP principles to achieve a robust and maintainable design:

### 1. **Encapsulation**  
   - User details like IDs and passwords, and election data (e.g., vote counts), are encapsulated within respective classes.
   - Access to these details is controlled via getter and setter methods.

### 2. **Inheritance**  
   - The `User` abstract class serves as the base for `Voter` and `Admin` classes, facilitating shared functionality such as login.

### 3. **Polymorphism**  
   - The `login()` method is overridden in both the `Voter` and `Admin` classes, tailoring behavior for each user type.

### 4. **Abstraction**  
   - Common properties and methods (e.g., `getId()`, `getName()`) are defined in the abstract `User` class, with specific actions implemented in derived classes.

---

## Integration with SDG 16
This project aligns with **Sustainable Development Goal (SDG) 16: Peace, Justice, and Strong Institutions**. It fosters:
- **Inclusivity**: Enabling all eligible users to participate in elections.
- **Transparency**: Ensuring fair and transparent electoral processes.
- **Civic Engagement**: Empowering users to exercise their voting rights in a secure digital environment.

By promoting democratic participation, the system contributes to building strong institutions and fostering trust in electoral processes.

---

## Example Screenshots

### 1. **Main Menu**
The main menu offers options for voters and admins to interact with the system.  
![Main Menu](screenshots/main_menu.png)

---

### 2. **Voter Registration**
Voters can sign up by providing their ID, name, and age.  
![Voter Registration](screenshots/voter_registration.png)

---

### 3. **Voting Process**
After logging in, voters can view a list of candidates and cast their vote.  
![Voting Process](screenshots/voting_process.png)

---

### 4. **Admin Dashboard**
Admins can manage elections, view results, and track election activities.  
![Admin Dashboard](screenshots/admin_dashboard.png)

---

### 5. **Election Results**
Admins can access and display real-time election results.  
![Election Results](screenshots/election_results.png)

---

## Instructions for Running the Program

### 1. Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/voting-system.git
cd voting-system
