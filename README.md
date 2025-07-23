### 🛠 Tools Used

* **Selenium** (for writing and executing test scripts using Python)
* **Chrome WebDriver**
* **PyCharm** (IDE for development and execution)

---

### 🚀 Steps to Run the Script

1. Install **PyCharm** or use any Python IDE of your choice.

2. Open the terminal and install the required dependencies:

   ```bash
   pip install selenium webdriver-manager pytest
   ```

3. Run the test script.

---

### 🌐 Website Under Test

**URL:** [https://lambdatest.github.io/sample-todo-app/](https://lambdatest.github.io/sample-todo-app/)

---

### ✅ Assumptions and Functionality

Assuming the website supports the creation of multiple to-do lists, each list offers comprehensive functionality, including the ability to **add**, **update**, and **delete** items—effectively implementing full **CRUD** operations.

The user interface is intuitive and user-friendly, featuring:

* Input fields for adding or editing items
* Buttons for saving changes or deleting items
* Checkboxes beside each item to allow users to mark tasks as completed

I utilized the above website to execute my Selenium test scripts, as it closely matches the functionality assumed in the test scenario. While the application allows adding tasks and marking them as complete, it does not explicitly provide a delete button. Instead, it simulates deletion by removing a task from the list once the associated checkbox is selected, treating the task as completed.

If a true delete button were available, the same testing logic would apply—locating the element via its **ID**, class, or other DOM attributes and performing the appropriate action using Selenium.
