[<img src="https://holbertonschool.com.au/wp-content/uploads/2023/02/Holberton-School.png">](https://holbertonschool.com.au/)

# Introduction to Design Patterns with Python

## Learning Objectives 🧠
Understand what design patterns are
- Distinguish between creational, behavioral, and structural patterns
- Explain what kind of problem each pattern solves
- Describe patterns as reusable design strategies rather than code templates

Apply the Factory pattern
- Identify the coupling caused by scattered direct instantiation
- Extend a factory registry to support a new type without modifying the core creation logic

Apply the Observer pattern
- Explain how a subject can publish events without knowing the concrete type of every listener
- Add a new observer and configure it to receive only specific topics

Apply the Decorator pattern
- Explain why composition can avoid subclass explosion
- Add a new decorator that composes correctly with existing ones without modifying any existing class

## Project File Table 📁
The following files are included in this project:
- all pycodestyle compliant

| File | Description |
| ---- | ----------- |
|[0-factory.py](0-factory.py) | Extend existing factory registry to support a new vehicle type without modifying the core creation logic inside create |
|[1-observer.py](1-observer.py) | Implement new observer and subscribe it to a running notification system, filtering it to recieve only specific event topics |
