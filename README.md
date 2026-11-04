# Pharmaceutical Calculations
## PharmCalc: Solution Strength Simulator

Welcome to PharmCalc, an interactive educational dashboard designed for pharmacy students, chemists, and formulation scientists. This tool bridges the gap between theoretical calculations and practical benchtop formulation by simulating dynamic concentration parameters in real-time.

Whether you are preparing a standard saline drip, compounding an ointment, or exploring the thermodynamic shifts between volume and mass-based concentrations, this dashboard allows you to visualize the math instantly.

## Features

Molarity (M): Calculate moles per liter for standard aqueous solutions.

Normality (N): Determine gram equivalent weights for pharmacopoeial titrations.

Molality (m): Calculate moles per kilogram of solvent for temperature-independent thermodynamics.

Percentage Expressions: Instantly compute % w/v, % w/w, and % v/v for IV bags, creams, and extracts.

Thermodynamic Conversions: A dedicated engine to convert between Molarity, Molality, and % w/w using solution density as the bridging metric.

First Principles Display: See the actual algebraic formulas updating in real-time to reinforce your fundamental understanding.
## Student Guide: How to Use This Tool

As a pharmacy student, you are expected to master manual calculations. Use this tool to verify your homework, check your lab prep sheets, and explore "what-if" scenarios.

1. Select Your Concentration Type

Navigate through the top menu to select the metric you are working with (Molarity, Normality, Molality, Percentages, or Thermodynamic Conversions).

2. Input Your Variables

Enter the known parameters (e.g., Mass, Molecular Weight, Volume) into the clean input fields.

Note on Units: Pay strict attention to the requested units in the input labels. Volumes are typically requested in mL (and auto-converted to Liters behind the scenes where necessary), while solvent mass for Molality is requested in kg.

3. Observe the Real-Time Results

As you type, the dashboard instantly recalculates the final concentration. The result is displayed in the highlighted blue box.

4. Review the "First Principles"

Below the result, you will see a typeset mathematical equation. This shows you exactly how the application arrived at the answer. Use this to double-check your own written formulas!

5. Master the Thermo Tab

The Thermodynamic Conversions tab is your secret weapon for advanced pharmaceutics. If you have a $1.2M$ solution and want to know its Molality, input the Molarity, the API's Molecular Weight, and the Solution Density ($\rho$). Observe how density acts as the bridge between volume-dependent and mass-dependent units.

## Local Setup (For Developers/Instructors)

This application is built entirely as a single-file, client-side HTML document. It requires no backend, no build steps, and no package managers.

Clone or download this repository.

Open index.html in any modern web browser (Chrome, Firefox, Safari, Edge).

The app utilizes Tailwind CSS (via CDN) for styling and MathJax for rendering LaTeX equations. Ensure you have an active internet connection the first time you load the page so these libraries can be cached.

## ⚠️  Academic Disclaimer ⚠️

This application is strictly for educational and simulation purposes. While the mathematical formulas are robust, always verify calculations manually or through validated institutional software before compounding or administering any actual pharmaceutical product.
