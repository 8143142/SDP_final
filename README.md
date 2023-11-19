<h3><b>Project name:</b> AutoCraftHub <br></h3>
<h3><b>Group:</b> SE-2216 <br></h3>
<h3><b>Team members:</b> Nauryzbay Tasbulat, Dauren Rysbek <br></h3>
<hr>
<h2>Project Overview:</h2><br><br>
The project is a car management system that incorporates various design patterns to achieve modularity, extensibility, and maintainability. The system involves creating and managing a car inventory within a car shop. Users can add new cars, add additional features to existing cars, delete cars from the inventory, apply chosen cars to the site, charge cars quickly, and observe changes in the car inventory.<br><br>
Idea of the Project:
<br>
The main idea of the project is to create a flexible and extensible system for managing cars within a shop. The project allows users to dynamically add features to cars, apply changes to the site, and observe inventory modifications in real-time. The system also incorporates charging options for cars, including a quick charging feature.<br><br>
Purpose of the Work:
<br>
The purpose of the project is to demonstrate the implementation of various design patterns in a real-world scenario. By developing a car management system, the project aims to showcase the practical application of patterns like Singleton, Observer, Decorator, Factory, Strategy, and Adapter. The project serves as an educational tool to understand how these patterns can enhance code structure and maintainability.<br><br>
Objectives of the Work:
<br>
Implement a car management system using Java.
Utilize design patterns to address different aspects of the system's functionality.
Showcase the practical application of Singleton, Observer, Decorator, Factory, Strategy, and Adapter patterns.
Provide a modular and extensible architecture for the car shop system.
Demonstrate dynamic feature addition to cars and real-time observation of inventory changes.
<hr>
<h2>Main body:</h2><br><br>
&#9675;Singleton Pattern (CarShop): Ensures a single instance of the CarShop exists, allowing centralized control of the car inventory.
<br>
&#9675;Observer Pattern (Observer, ConsoleObserver): Enables the CarShop to notify observers (such as ConsoleObserver) about changes in the car inventory, providing a real-time update mechanism.

&#9675;Decorator Pattern (CarDecorator, LedHeadlightsDecorator, FastChargingDecorator, WinterWheelsDecorator): Allows the dynamic addition of features to cars without modifying their core implementation. Each decorator extends the functionality of the base Car class.

&#9675;Factory Pattern (CarFactory): Encapsulates the process of creating cars, providing a flexible way to instantiate different types of cars.

&#9675;Strategy Pattern (CarStrategy): Defines a strategy for adding features to a car. Concrete strategies like WinterWheelsStrategy and LedHeadlightsStrategy can be implemented.

&#9675;Adapter Pattern (QuickChargingAdapter): Adapts the interface to enable quick charging for cars. It bridges the gap between the existing Car interface and the specific quick charging implementation.<br>
