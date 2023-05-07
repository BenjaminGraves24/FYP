=============================
Hydrogen Economy Forecast GUI
=============================

:Author: Benjamin Graves
:Supervisor: Dr. Rick Lupton
:Project Title: Assessing the Viability of Hydrogen in Decarbonising the UK Economy: A Data-Driven Analysis of Supply, Demand, and Progress Towards the 10 GW 2030 Hydrogen Capacity Target

Overview
========

This code creates a graphical user interface (GUI) that allows users to view Sankey diagrams visualizing the forecasts of the 2030 Hydrogen Economy from a variety of sources.

Dependencies
============

- Python 3
- floweaver
- ipywidgets
- IPython

Usage
=====

To use this code, first ensure all required dependencies are installed. Then, simply run the code in a Jupyter Notebook or Jupyter Lab environment. The GUI will be displayed, allowing users to view different Sankey diagrams by selecting from the available options.

Code Structure
==============

1. Import required libraries
2. Define the dimensions of the Sankey diagrams
3. Load data from CSV files
4. Define process groups and nodes for Sankey diagrams
5. Define ordering and bundles for Sankey diagrams
6. Define color scheme
7. Create Sankey diagrams for each case using the defined nodes, bundles, and ordering
8. Create output widgets to display Sankey diagrams
9. Create buttons for user interaction, and define button click events
10. Display the GUI with header buttons, subbuttons, and output widgets
