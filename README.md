# MonolithicAdventureGame-Homework-1
How Students Should Approach Refactoring This Code:
Identify Responsibilities:
Player Management: Handling health, experience, and inventory.
Combat: Determining enemy interactions and updating state.
Item Management: Processing item pickups and related effects.
Level Progression: Handling level advancement and associated state changes.
Apply SOLID Principles:
Single Responsibility Principle (SRP): Split the responsibilities into distinct classes (e.g., Player, EnemyManager, ItemManager, LevelManager).
Open/Closed Principle (OCP): Design the system so that new enemy or item types can be added without modifying existing classes.
Dependency Inversion Principle (DIP): Introduce interfaces where applicable (e.g., for managing combat or inventory) to decouple high-level modules from low-level details.
Liskov Substitution Principle (LSP): Ensure that any derived or alternative implementations can replace the existing ones without changing the expected behavior.
Interface Segregation Principle (ISP): If needed, split large interfaces into more focused ones that are client-specific.
Documentation and UML Diagrams:
Require a brief write-up explaining how the refactoring addresses SOLID principles.
Optionally, include UML diagrams to visualize the new class structure.
Submission:
Submit the refactored code and documentation according to the homework instructions.
