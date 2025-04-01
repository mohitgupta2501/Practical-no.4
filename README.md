# Practical-no.4

### **Use Case Diagrams for Ayurvedic Management System**  

#### **Introduction**  
A **Use Case Diagram** is a visual representation of how different users (actors) interact with a system. In the case of an **Ayurvedic Management System**, this diagram helps define the system's functionalities, ensuring smooth operations for Ayurvedic practitioners, patients, and administrators.  

The **Ayurvedic Management System** focuses on **patient management, herbal medicine inventory, appointment scheduling, and personalized treatment plans** based on Ayurveda principles.  

#### **Actors in the System**  
1. **Primary Actors**  
   - **Doctor (Ayurvedic Practitioner)** – Provides consultations, prescribes treatments, and manages patient history.  
   - **Patient** – Books appointments, receives Ayurvedic treatment plans, and accesses prescriptions.  
   - **Admin/Receptionist** – Manages appointments, maintains records, and handles billing.  

2. **Supporting Actors**  
   - **Herbal Medicine Inventory System** – Tracks the availability of herbal medicines.  
   - **Payment Gateway** – Handles online transactions for consultation and medicines.  

#### **Use Cases**  
1. **Patient Registration** – New patients sign up and provide health details for Ayurvedic diagnosis.  
2. **Appointment Booking** – Patients schedule appointments with Ayurvedic doctors.  
3. **Consultation & Diagnosis** – The doctor examines patients based on Ayurvedic principles and prescribes treatment.  
4. **Herbal Medicine Prescription** – The system suggests herbal medicines based on the patient’s condition.  
5. **Inventory Management** – Tracks the availability of herbs and Ayurvedic medicines.  
6. **Billing & Payment Processing** – Generates bills for consultations and herbal medicines.  
7. **Health Report Generation** – Stores patient history and generates reports for future reference.  

#### **Graphical Representation - Use Case Diagram**  
The **Use Case Diagram** will depict:  
- The relationship between **patients, doctors, and administrators** with the system.  
- The **include relationship** where "Health Report Generation" depends on "Consultation & Diagnosis."  
- The **extend relationship** where "Billing & Payment Processing" extends "Appointment Booking."  

#### **Use Case Relationships**  
- **Include Relationship:** "Herbal Medicine Prescription" **includes** "Consultation & Diagnosis" since medicines are prescribed based on diagnosis.  
- **Extend Relationship:** "Health Report Generation" **extends** "Consultation & Diagnosis" as reports are only generated after patient interaction.  

#### **Identifying Actors and Use Cases**  
To develop an efficient **Ayurvedic Management System**, we need to:  
- Identify **who interacts** with the system (actors).  
- Determine **what functionalities** the system must provide (use cases).  
- Define **relationships** among use cases to ensure a structured workflow.  

#### **Case Study Example**  
Consider an Ayurvedic clinic where **patients book appointments online**. After a consultation, the doctor **prescribes herbal medicines** and **generates health reports**. The **admin updates the inventory**, and payments are processed through an integrated **billing system**. This ensures a **smooth and systematic Ayurvedic healthcare process**.  

#### **Conclusion**  
A **UML Use Case Diagram** is essential for designing a structured **Ayurvedic Management System**. It helps define **functional requirements**, streamline **clinic operations**, and improve **patient care** through **efficient diagnosis, treatment planning, and herbal medicine management**.  

---

![image](https://github.com/user-attachments/assets/db03f67f-75e9-4473-9a28-1ea3f1938033)
