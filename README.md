# Employee Management System (OOP Wrapper)

A clean, modular Python application that demonstrates the core pillars of **Object-Oriented Programming (OOP)**. This system allows for the management of a corporate hierarchy, specifically handling Managers and Developers through inheritance and polymorphism.

---

## 🌟 Features

* **Hierarchical Structure:** Utilizes class inheritance to derive `Manager` and `Developer` roles from a base `Employee` class.
* **Polymorphism:** Implements method overriding for `get_details()` to ensure each employee type displays its specific role correctly.
* **CRUD Operations:** * **Create:** Add new Managers or Developers with unique IDs.
* **Read:** View a formatted list of all current staff.
* **Delete:** Remove records from the system using a specific Employee ID.


* **State Management:** The `EmployeeSystem` class acts as a wrapper to manage the lifecycle and storage of employee objects.

---

## 🛠️ Technical Breakdown

| Concept | Implementation in `5_OOP_Wrapper.py` |
| --- | --- |
| **Inheritance** | `Manager` and `Developer` inherit attributes from the `Employee` base class. |
| **Encapsulation** | Employee data (ID, Name, Age, Salary) is bundled within object instances. |
| **Super Function** | Uses `super().__init__()` to properly initialize base class attributes in subclasses. |
| **List Management** | Dynamic storage of objects using Python lists within the `EmployeeSystem`. |

---

2. **Add Staff:** Choose between adding a **Manager** (Option 1) or a **Developer** (Option 2).
3. **Input Details:** Enter the ID, Name, Age, and Salary when prompted.
4. **View Records:** Use Option 3 to see the current roster in a structured pipe-separated format.
5. **Remove Staff:** Use Option 4 and provide the exact ID to delete an entry.

---

## 👤 Author

** Aesha makrubiya**

---
