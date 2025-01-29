# Task-Tracker-Project-in-Python-using-Enumerators

An enumeration is a symbolic name for a set of values, often used to represent a fixed set of constants. Python has a built-in Enum class in the enum module that allows us to define enumerations.

Let’s create a small project to manage a task status tracker with different statuses using Enum. The task could have the following statuses: Pending, In Progress, and Completed.

Step 1: Define the Enum
We'll start by defining the TaskStatus enumeration using the Enum class.

Step 2: Create a Task Class
The Task class will use the TaskStatus enumeration to set and track the task's current status.

Step 3: Implement a Simple Workflow
We'll add a simple workflow where you can change the status of a task.

TaskStatus Enum:

We define an enum TaskStatus with three possible values: PENDING, IN_PROGRESS, and COMPLETED.
We also override the __str__ method in the Enum class to format the status names in a more user-friendly way (replacing underscores with spaces and capitalizing the words).
Task Class:

The Task class represents a task with a name and a status.
Initially, the status is set to PENDING.
The change_status method allows us to change the task's status, ensuring it's a valid TaskStatus.
Main Function:

In the main function, we create a Task object and simulate changing its status through various stages (from Pending to In Progress to Completed).

