# RAP100: SAP BTP ABAP Environment Tutorial

This project contains the implementation of a UI service developed using the **ABAP RESTful Application Programming Model (RAP)**. It was built following the SAP developer tutorial mission on the SAP BTP ABAP Environment.

The application is a Fiori elements-based project that demonstrates core RAP concepts, including managed implementation, internal unmanaged numbering, and transactional business logic.

---

## 🚀 Project Overview

The project provides a comprehensive look at the modern ABAP development workflow using ADT (ABAP Development Tools). Key features implemented include:

* **Managed Implementation:** RAP handles standard CRUD operations automatically.
* **Internal Unmanaged Numbering:** Business object keys are generated programmatically during the save sequence.
* **Transactional Behavior:** Business logic implemented via:
    * **Determinations:** To automatically update fields based on state changes.
    * **Validations:** To ensure data integrity before saving.
    * **Actions:** To execute specific business processes on the entity.

## 🛠 Technical Stack

* **Platform:** SAP BTP, ABAP Environment (Trial)
* **Development Tools:** ABAP Development Tools (ADT)
* **Programming Model:** ABAP RESTful Application Programming Model (RAP)
* **UI Framework:** SAP Fiori elements

## 📂 Project Structure

This project includes the following generated and custom-coded artifacts:

* **Database Table:** The foundation of the business object.
* **CDS Data Model:** Projection and interface views for the Fiori UI.
* **Behavior Definition:** Defining the transactional capabilities and internal numbering.
* **Behavior Implementation:** ABAP classes containing the logic for determinations, validations, and actions.
* **Service Definition & Binding:** Exposing the OData service for the Fiori application.

## 📝 Setup & Deployment

1.  **Environment:** Ensure you have access to an SAP BTP ABAP Environment instance.
2.  **ADT:** Import this project into your ADT workspace.
3.  **Transport/Activation:** Ensure all artifacts are activated in your development package.
4.  **Service Preview:** Use the Service Binding in ADT to launch the Fiori elements preview.

## 🎓 About This Project

This project was developed as part of the official SAP tutorial mission for RAP100. It serves as a practical reference for developers learning to build cloud-ready applications on the SAP BTP ABAP Environment.

---

*Happy Coding!*
