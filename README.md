# Transport Costing and Chargeable Weight Analysis
 Analyzing transportation costs and chargeable weight to optimize logistics and supply chain efficiency, using Excel and Python, and providing actionable insights for cost reduction and improved decision-making
Project Overview

This project focuses on analyzing the transport costing and chargeable weight of goods across various transportation modes. The goal is to provide insights into cost optimization, evaluate chargeable weight based on dimensional and actual weight calculations, and recommend improvements for better cost efficiency in supply chain operations. The project also demonstrates how to use Excel-based data analysis techniques to assess transportation costs.
Dataset

The provided dataset (Chargeable Weight Exercise - Transport Costing.xlsx) contains the following details:

    Shipment dimensions (length, width, height)
    Actual weight
    Freight rates per transportation mode
    Cost components (e.g., fuel surcharge, handling fees)
    Origin and destination

Key Objectives

    Chargeable Weight Calculation: Determine the chargeable weight for shipments based on dimensional and actual weight comparisons.
    Cost Analysis: Evaluate the total cost incurred for each shipment across various transportation modes.
    Optimization Insights: Provide recommendations on how to minimize transportation costs by optimizing shipment packaging and choosing the most cost-effective transportation mode.

Methodology

    Data Preparation:
        The dataset is cleaned and structured for analysis. Any missing or erroneous data is identified and handled.

    Chargeable Weight Calculation:
        Chargeable weight is calculated based on both dimensional and actual weight.
        The higher of the two weights is considered for calculating transportation costs.

    Cost Calculation:
        Freight rates are applied based on the chargeable weight.
        Additional costs, such as fuel surcharges and handling fees, are included to determine the total cost per shipment.

    Analysis and Insights:
        Compare the total costs across different shipment options.
        Provide insights into how chargeable weight influences overall transportation costs.

Technologies Used

    Excel: The dataset is processed and analyzed using Microsoft Excel. Functions like SUMIFS, IF, and VLOOKUP are used for data calculation and cost aggregation.
    Python (Optional Extension): For advanced users, the analysis can be extended using Python for automated cost calculations and visualizations.

How to Use

    Clone the repository:

    bash

git clone https://github.com/yourusername/transport-costing-analysis.git

Navigate to the project directory and open the Chargeable Weight Exercise - Transport Costing.xlsx file to review the raw data.

Perform your analysis by following the steps outlined in the methodology section.

(Optional) If you are using Python for automated analysis, run the provided Python script:

bash

    python transport_cost_analysis.py

Results

    A detailed breakdown of transportation costs based on chargeable weight is available in the Excel sheet.
    Recommendations for optimizing transportation costs will be provided based on the analysis results.

Future Improvements

    Automated Calculation: Implement a Python script for fully automating the calculation of chargeable weights and transportation costs.
    Visualization: Create visualizations (charts and graphs) to better illustrate cost differences between transportation modes.
    Integration with Real-Time Data: Connect the analysis to a real-time data feed from logistics providers for dynamic cost calculation and optimization.

Contributing

Contributions are welcome! If you'd like to enhance the project, feel free to submit a pull request or open an issue.
License

This project is licensed under the MIT License - see the LICENSE file for details.
