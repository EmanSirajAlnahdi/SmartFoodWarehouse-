#  Warehouse Automation Project – Transforming a Food Warehouse into a Fully Automated Facility

The goal of this project is to design an algorithm to convert a food warehouse into a fully automated smart warehouse **without human intervention**, using robotics and artificial intelligence technologies.

---

##  Execution Algorithm

1. **Analyzing the current warehouse environment:**
   - Collecting data on the warehouse size, types of food items, storage methods, and aisles.
   - Identifying receiving, storage, and distribution points.
   - Drawing a 3D map using LiDAR and analyzing congestion points to identify ideal automation zones.

2. **Identifying tasks that can be automated:**
   - Receiving shipments, internal transport, storage, order picking, and shipping.
   - Classifying tasks based on their automation potential and assigning the appropriate technical solution for each.

3. **Selecting the appropriate types of robots:**
   - Mobile robots (AMRs) for material transportation.
   - Robotic arms for loading and organizing.
   - Computer vision systems for recognition and classification.
   - A smart centralized management system (WMS).

4. **Designing the mechanical and electronic system:**
   - Planning robot paths and placing sensors and cameras.
   - Preparing the floor with smart guidance systems (e.g., RFID and QR).
   - Developing a fully integrated communication network.

5. **Programming the system:**
   - Developing AI algorithms for product recognition and navigation optimization.
   - Integrating data with the ERP system for real-time inventory updates.
   - Building a digital control dashboard for monitoring and management.

6. **Implementing a prototype:**
   - Testing the system in a small area of the warehouse.
   - Evaluating robot-item interaction and performance.
   - Adjusting programming as needed before full-scale deployment.

7. **Gradual expansion:**
   - Rolling out the system to remaining warehouse sections step-by-step.
   - Training human staff to monitor rather than intervene.
   - Analyzing each phase to improve the next one.

8. **Maintenance and support:**
   - Setting up a real-time alert system for failures.
   - Smart periodic maintenance scheduling for each robot.
   - Developing an app for remote performance monitoring and technical support.

---

## Working Envelope Elements

### 1. Transport Robots (AMRs)
- Move freely in the warehouse ground aisles.
- Require aisle width of at least 80 cm.
- Rely on SLAM and sensors to avoid obstacles.
- Entire working envelope is horizontal across the floor.

### 2. Robotic Arms
- Operate within a circular radius up to 1.5 meters.
- Work height reaches up to 2.5 meters.
- Equipped with 6 Degrees of Freedom (DOF) for precise access.
- Use inverse kinematics to determine optimal movement.

### 3. Vision Systems
- Cover a field of view ranging from 120° to 360°.
- Installed at strategic high locations.
- Use AI to analyze images and recognize products.

### 4. Auto-Charging Docks
- Strategically distributed throughout the warehouse.
- Allow robots to self-charge when needed.
- Equipped with sensors to guide robots accurately to the dock.
- Must be located within the robots’ working envelope.

---

## Author: Eman Alnahdi.
