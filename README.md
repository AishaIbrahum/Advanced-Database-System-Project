# Advanced-Database-System-Project
# Scenario:
This cutting-edge database revolutionizes blood bank operations, empowering managers to:
Manage staff, donors, and patients seamlessly.
Find available blood samples instantly, saving valuable time.
Optimize inventory to minimize waste and ensure availability.
Analyze data to make informed decisions and improve efficiency.

##### Designed for practicality, the system is:
User-friendly and easy to manage.
Time-saving and efficient.
Cost-effective and resource-efficient.
Flexible and adaptable to changing needs.
##### By implementing this system, blood banks can:
Enhance patient care with timely access to blood products.
Streamline operations for greater efficiency.
Revolutionize their services to meet evolving demands.
# DB planning:

#### Effective Database Development and Management
Efficient database development and management require a structured approach that ensures each phase of the lifecycle is executed proficiently and cost-effectively. A crucial initial step in database planning is to clearly define the project's mission statement and objectives.
#### Mission Statement
The mission statement concisely captures the database system's primary purpose and goals. It outlines the reasons for its existence and the value it aims to deliver. A well-crafted mission statement provides a clear direction for the development team and ensures that the system aligns with the organization's strategic objectives.
#### Mission Objective
A mission objective establishes a specific, measurable, achievable, relevant, and time-bound goal that the database system must help achieve. It serves as a tangible target for the development team and ensures that the system delivers tangible value to the organization. By defining clear mission objectives, organizations can ensure that their database systems contribute directly to their overall success.
This enhanced response provides a more detailed explanation of the importance of a clear mission statement and mission objectives in database development and management. It emphasizes their role in guiding the development process, ensuring alignment with organizational goals, and delivering tangible value to the enterprise.
# System Definition :
Describes scope and boundaries of database system and the major user views.
## 1-Scope and Boundaries:
<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/3ef0d828-a27b-4d37-95b5-d90ad886e093" width="400" alt="My image">

# 2- Major User Views:
<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/1001dad7-2084-47ec-9187-f1600e1c0c0b"  width="400" alt="My image">

# 3- Cross-Reference of User Views:

<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/53e0ded4-fd6f-4607-9e5d-7c6c5c1255b9"width="400"alt="My image">

# 4-Requirement collection and analysis:
We have used the technique of open-ended questionnaires

<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/eb0e33e4-e94f-4d42-ba2c-af93e607bb5c" width="400" alt="My image">

# ER MODEL:

<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/c69ddef7-dfb0-47bb-ad23-67814b0cbc59" width="400" alt="My image">

# ER MAPPING SCHEMAS:

<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/60ae47e7-035b-497c-8640-73b494786d9a" width="400" alt="My image">

# RELATIONSHIP BETWEEN ENTITIES:
1- Staff and Donor: -Relationship = “registers” Type of relation = 1 to many Explanation = One recording staff can register many donors. One donor will register with one recording officer. The relationship with Recording staff and Donor is 1 to many. That’s why primary key of Recording staff is used as a foreign key in Donor.
2- Staff and patients: -Relationship = “record” Type of relation = 1 to many Explanation = One recording staff can record many patients. One patient will be recorded by one recording staff. The relationship with staff and patients is 1 to many. That’s why primary key of staff is used as a foreign key in patients.
3- patients and Manager: -Relationship =“requests in ” Type of relation = 1 to many Explanation = One patients can request blood to one manager and one manager can handle requests from many patients. The relationship with Blood Bank Manager and patients is 1 to many. That’s why primary key of Blood Manager is used as a foreign key in patients
4- Hospital and Manager: -Relationship = “gives order ” Type of relation = 1 to many Explanation = One Blood bank manager can handle and process requests from many hospitals. One hospital will place request to on blood bank manager The relationship with Blood Bank Manager and Hospital info is 1 to many. That’s why primary key of Blood Bank manager is used as a foreign key in Hospital info.
5- Manager and Blood Specimen: -Relationship = “deales with ” Type of relation = 1 to many Explanation = One Blood bank manager can manage many blood specimen and one specimen will be managed by one manager. The relationship with Blood Bank manager and Blood Specimen is 1 to many. That’s why primary key of Blood Bank manager is used as a foreign key in Blood Specimen

# Logical database Design:

<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/e333eacc-933f-4daa-8a47-a87f963999c9"   width="400" alt="My image">

# Physical database Design:

<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/f29cbf88-1ece-499d-ad0e-90d74565b3bb" width="400" alt="My image">

# DBMS selection:
### 1- Determine and study requirements:
<img src="https://github.com/AishaIbrahum/Advanced-Database-Design-and-Implementation-of-a-Blood-Bank-Management-System/assets/143902740/dd181fe0-2a77-4fb7-bd0b-73c7bd2886c4" width="400"  alt="My image"> 

### 2- shortlist two or three products:
MySQL
MongoDB
Amazon Simple Storage Service (S3)
Elasticsearch
### 3-evaluate products:
MySQL
MongoDB
Amazon Simple Storage Service (S3)
Elasticsearch 5- recommend selection and produce report

