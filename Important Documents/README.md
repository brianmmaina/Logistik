# Truck_management_system
**Truck management system for mock client. **
## Project Overview

### Criteria A: Defining the Problem

#### Client Background
The client, Mr. S, is a logistics manager for a fuel/oil transportation company. Currently, Mr. S relies on Excel documents and handwritten notes to track the locations, truck and trailer IDs, and driver information. This system has proven to be inefficient as it is:
- **Time-consuming:** Searching for specific information requires manual effort.
- **Error-prone:** Human errors occur due to outdated and inconsistent documentation (Appendix A).

Additionally, coordinating with drivers is managed via text messages and calls, which presents several issues:
- **Inefficiency:** Drivers, often on long road trips, have limited time to relay information.
- **Safety concerns:** Communicating via calls or texts while driving increases the risk of accidents (Appendix A).

#### Rationale for the Program
To address these challenges, the proposed program will be developed using **Java** in the **NetBeans IDE**. Key advantages of this approach include:
- **Portability:** The software can run on multiple devices and in various locations.
- **User-friendliness:** NetBeans enables the development of a Graphical User Interface (GUI) for ease of use.
- **Functionality:** The program will:
  - Allow managers to view driver inputs in tabular and graphical formats.
  - Display truck availability, locations, and capacity in visualized formats (e.g., pie charts).
  - Implement a dropdown menu for hierarchical access based on user roles (Manager or Driver).
  - Use a secure username and password system stored in random access files.

### Success Criteria
The following features define the success of the program:
1. **Login Hierarchy:** A dropdown menu for credentials differentiating Managers and Drivers.
2. **Role-Specific Panels:** 
   - Managers: View and filter data.
   - Drivers: Input and update journey details.
3. **Driver Features:**
   - Input location of the truck.
   - Input truck and trailer IDs.
   - Update activity status.
   - Add their name and journey updates.
4. **Data Storage:** All driver inputs are securely stored in a MySQL database.
5. **Manager Features:**
   - View driver inputs in a table format.
   - Display a pie chart showing total available capacity.
   - Refresh the table to reflect new driver inputs.
   - Filter data for specific details.

By meeting these criteria, the program will significantly improve the efficiency and safety of logistics management for Mr. S’s company.
