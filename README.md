Smart Vehicle Classifier

A beginner-friendly Python project that demonstrates core OOP concepts:
**classes, inheritance, encapsulation (protected/private), properties, and method overriding**.
It classifies vehicles (Car/Bike) by a speed threshold and prints formatted details.

---

## Features
- Base class `Vehicle` with:
  - Protected attribute: `_vehicle_type`
  - Private attributes: `__name`, `__speed`
  - Properties with validation: `name`, `speed`
  - `classify()` → High-speed (> 100) vs Normal
- Subclasses `Car` and `Bike` overriding `show_info()`
- Simple factory function `create_vehicle()` to build the right subclass
- Interactive input flow (works well in Colab or terminal)

---

##  Files
- `Smart Vehicle Classifier.ipynb` — Google Colab/Jupyter notebook version
- *(optional, recommended)* `smart_vehicle_classifier.py` — plain Python script version  
  > Tip: you can add this later by uploading your `.py` file.

---

## How to run

### Notebook (Google Colab/Jupyter)
1. Open `Smart Vehicle Classifier.ipynb`.
2. Run cells in order.
3. For the interactive version, follow the prompts.


Paste input like:
3
Car Toyota 150
Bike Yamaha 90
Car Honda 120

## Sample Input
3
Car Toyota 150
Bike Yamaha 90
Car Honda 120

## Expected Output
Car Added: Toyota
Bike Added: Yamaha
Car Added: Honda

--- Vehicle Details ---
Type: Car, Name: Toyota, Speed: 150 km/h, Predicted: High-speed Vehicle
Type: Bike, Name: Yamaha, Speed: 90 km/h, Predicted: Normal Vehicle
Type: Car, Name: Honda, Speed: 120 km/h, Predicted: High-speed Vehicle
