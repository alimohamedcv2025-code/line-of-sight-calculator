# Line of Sight Calculator | Premium Edition

A modern, interactive web-based tool for calculating the radio horizon and maximum line of sight (LOS) between two communication stations.

Designed with a clean glassmorphism interface and smooth animations, this tool is suitable for students, engineers, and anyone working with wireless communication systems.

---

## Features

* Calculate radio horizon for two stations
* Compute total line of sight (LOS)
* Supports:

  * Metres
  * Feet (automatically converted to metres)
* Smooth animated result updates
* Modern UI design (glassmorphism with gradient background)
* Press Enter to calculate instantly
* One-click reset (Clear All)

---

## Formula Used

The calculator is based on the radio horizon formula:

```
d = 3.57 × √(K × h)
```

Where:

* d = distance in kilometers
* h = antenna height in meters
* K = 4/3 (Earth curvature factor)

Total Line of Sight:

```
LOS = d1 + d2
```

---

## Technologies Used

* HTML5
* CSS3 (animations and modern UI styling)
* Vanilla JavaScript

---

## Project Structure

```
Line-Of-Sight-Calculator
 ├── index.html
 └── README.md
```

---

## How to Use

1. Open the project in your browser
2. Enter:

   * Height of first antenna
   * Height of second antenna
3. Select the unit (Metres or Feet)
4. Click "Calculate Now" or press Enter
5. View the results:

   * Radio Horizon (Station 1)
   * Radio Horizon (Station 2)
   * Total Line of Sight

---

## Example

Input:

* Height 1 = 50 m
* Height 2 = 100 m

Output:

* Horizon 1 ≈ 29.15 km
* Horizon 2 ≈ 41.21 km
* Total LOS ≈ 70.36 km

---

## Use Cases

* Wireless communication planning
* Network engineering (RF links)
* Educational purposes
* Telecom simulations

---

## Future Improvements

* Add graph visualization
* Map-based distance plotting
* Mobile application version
* Frequency-based adjustments
  
---

