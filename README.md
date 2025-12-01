🏎️ Race Tools Console
The Race Tools Console is a single-page web application designed to assist racing teams and sim racers in planning complex endurance strategies, managing fuel loads, and optimizing car setup for various racing formats.
The application is built entirely in a single HTML file, making it highly portable and ideal for rapid deployment on platforms like GitHub Pages.

✨ Features 
This console is split into three core modules to cover all aspects of race strategy:
1. Endurance Strategy Planner
 * Optimal Stint Calculation: Determines the maximum safe stint length based on the most restrictive factor: Driver time limits, Tire wear limits, or Fuel capacity.
 * Race Breakdown: Calculates the total number of laps, total fuel required, and the exact number of pit stops necessary for the race distance.
 * Pit Stop Sequence: Generates a detailed, driver-swapped pit stop sequence table, showing the stop number, stint laps, driver assignments, and fuel required for each stop.
2. Simple Fuel Calculator
 * Provides a quick tool to determine the required fuel load (in liters) for a specific number of target laps or a target time duration, including a user-defined safety margin.
3. Setup Advisor
 * Offers instant recommendations for car setup adjustments (e.g., spring rates, anti-roll bars, brake bias) based on the balance issue (Understeer or Oversteer) and the specific corner phase (Entry, Mid, or Exit) where the issue occurs.

Planning a Race
 * Navigate to the Strategy Planner tab.
 * Input your Race Duration, Average Lap Time, and key constraint parameters (Max Driver Stint, Max Tire Stint, Fuel Consumption, etc.).
 * Click Generate Strategy.
 * The system will output the Optimal Stint Length (identifying the limiting factor) and a detailed Pit Stop Sequence table.
🛠️ Technology Stack
 * HTML5: Application structure.
 * Tailwind CSS: For all styling, ensuring a clean, modern, and fully responsive "digital console" aesthetic.
 * JavaScript (Vanilla): All logic and calculations, operating without external frameworks or dependencies.
