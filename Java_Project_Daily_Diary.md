# 📘 Java Project – Daily Diary  
**Name:**Deepa Basnet  
**Project Title:** Event Management System (Java)  
**Duration:** 23 June 2025 – 21 July 2025  
**Platform:** Java, MySQL, NetBeans / IntelliJ IDEA  
**Repository:** [GitHub Repo Link](https://github.com/)  

---

## 📅 Navigation
[Day 1](#day-1---23-june-2025) | [Day 2](#day-2---24-june-2025) | [Day 3](#day-3---25-june-2025) | [Day 4](#day-4---26-june-2025) | [Day 5](#day-5---27-june-2025)  
[Day 6](#day-6---30-june-2025) | [Day 7](#day-7---1-july-2025) | [Day 8](#day-8---2-july-2025) | [Day 9](#day-9---3-july-2025) | [Day 10](#day-10---4-july-2025)  
[Day 11](#day-11---7-july-2025) | [Day 12](#day-12---9-july-2025) | [Day 13](#day-13---11-july-2025) | [Day 14](#day-14---15-july-2025) | [Day 15](#day-15---18-july-2025)  

---

## 📝 **Day 1 – 23 June 2025**
### Work Done
- Attended project briefing session.  
- Selected **Event Management System** as the project topic.  
- Installed JDK, NetBeans, and configured environment variables.  
- Created a new Java project and basic folder structure.

### Challenges / Issues
- Faced minor issues while setting environment variables for JDK.  

### Next Plan
- Research about event modules and database schema.

---

## 📝 **Day 2 – 24 June 2025**
### Work Done
- Understood project requirements.  
- Created basic **UML diagrams** for system design (Use Case, Class Diagram).  
- Finalized main modules: Admin, User, Event Organizer.

### Challenges / Issues
- Difficulty deciding table relationships for events and users.

### Next Plan
- Design database schema in MySQL.

---

## 📝 **Day 3 – 25 June 2025**
### Work Done
- Created database named `event_db`.  
- Added tables: `users`, `events`, `bookings`.  
- Connected database with Java using JDBC.

### Challenges / Issues
- JDBC driver not recognized initially (resolved by adding MySQL connector).  

### Next Plan
- Start working on Admin Login module.

---

## 📝 **Day 4 – 26 June 2025**
### Work Done
- Implemented **Admin Login** with validation.  
- Added GUI using `JFrame` and `JPanel`.  
- Tested login with sample credentials.

### Challenges / Issues
- GUI alignment issues due to layout manager conflicts.

### Next Plan
- Work on event creation form.

---

## 📝 **Day 5 – 27 June 2025**
### Work Done
- Developed **Add Event** form with fields (Name, Date, Venue, Description).  
- Added SQL insert functionality for new events.  
- Successfully stored sample event data in database.

### Challenges / Issues
- Validation errors for date input; fixed with `SimpleDateFormat`.

### Next Plan
- Add event display and delete features.

---

## 📝 **Day 6 – 30 June 2025**
### Work Done
- Displayed list of events from database in JTable.  
- Implemented delete event functionality.  
- Added confirmation dialog before deletion.

### Challenges / Issues
- Data not refreshing automatically after deletion (solved with `model.fireTableDataChanged()`).

### Next Plan
- Begin work on **User Registration** page.

---

## 📝 **Day 7 – 1 July 2025**
### Work Done
- Created **User Registration** form with validation.  
- Added password encryption using `MessageDigest`.  
- Integrated with database table `users`.

### Challenges / Issues
- Faced `SQLIntegrityConstraintViolationException` for duplicate usernames.

### Next Plan
- Design User Login and dashboard.

---

## 📝 **Day 8 – 2 July 2025**
### Work Done
- Completed **User Login** page.  
- Created **User Dashboard** showing available events.  
- Enabled event booking by users.

### Challenges / Issues
- Event booking records not updating due to wrong query syntax (fixed).

### Next Plan
- Add booking history and cancel booking option.

---

## 📝 **Day 9 – 3 July 2025**
### Work Done
- Added **Booking History** section for users.  
- Implemented event cancel feature.  
- Enhanced UI with icons and better layout.

### Challenges / Issues
- Trouble refreshing booking list after cancel operation.

### Next Plan
- Work on search and filter options for events.

---

## 📝 **Day 10 – 4 July 2025**
### Work Done
- Added event search by name and date.  
- Improved Admin dashboard UI.  
- Connected modules together for full navigation.

### Challenges / Issues
- Button event listeners overlapping in multiple forms.

### Next Plan
- Start testing phase and fix UI bugs.

---

## 📝 **Day 11 – 7 July 2025**
### Work Done
- Tested all modules for errors.  
- Fixed layout inconsistencies.  
- Added “About Project” and “Help” sections.

### Challenges / Issues
- Application freezing on large query loads (optimized queries).

### Next Plan
- Prepare report documentation.

---

## 📝 **Day 12 – 9 July 2025**
### Work Done
- Created project documentation structure.  
- Wrote introduction and objective sections.  
- Took screenshots of modules for report.

### Challenges / Issues
- Some screenshots not saving correctly; re-captured.

### Next Plan
- Write theoretical background section.

---

## 📝 **Day 13 – 11 July 2025**
### Work Done
- Completed **System Design** and **Implementation** sections of report.  
- Added ER Diagram and Data Flow Diagram.  

### Challenges / Issues
- Diagram exports were blurry; redone in higher resolution.

### Next Plan
- Finalize testing and conclusion section.

---

## 📝 **Day 14 – 15 July 2025**
### Work Done
- Wrote **Testing & Result Analysis** section.  
- Verified all modules functionality one last time.  
- Performed demo presentation run.

### Challenges / Issues
- Minor alignment issue in booking history table.

### Next Plan
- Finalize project documentation.

---

## 📝 **Day 15 – 18 July 2025**
### Work Done
- Finalized and formatted full report.  
- Created PowerPoint presentation.  
- Uploaded complete project to GitHub.  
- Prepared for viva and final submission.

### Challenges / Issues
- Needed to rename some files for compatibility.

### Next Plan
- Submit project and demonstrate to faculty.

---

## 🧩 **Conclusion**
The 4-week Java project training was successfully completed.  
Through this period, I learned about GUI programming, JDBC connectivity, database design, and debugging techniques.  
The Event Management System project helped me understand end-to-end Java application development from planning to deployment.
