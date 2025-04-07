<img width="350" alt="hartman-logo-png" src="https://github.com/user-attachments/assets/604b9209-f493-4a29-89f8-b4e408d7a166" />

# The Hartman App: Plastics Supply Chain Forecasting Tool

## Summary

**The Hartman App** is a dynamic, user-friendly tool designed to help businesses in the plastics industry forecast the impact of tariffs, costs, and taxes on their supply chain. Inspired by **James Hartman**, the President and Founder of **American Plastics Supply & Designer Plastics**, this app focuses on predicting and adjusting key metrics, such as **import costs**, **domestic costs**, **tax revenues**, and **production costs**, to ensure more accurate decision-making. 

This application is built to support both technical and non-technical users with easy-to-understand graphs, forecasts, and downloadable reports. By leveraging data from the **China–U.S. tariff battles**, this app empowers businesses to make informed decisions about sourcing materials and navigating the complexities of international trade.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Why This Matters](#why-this-matters)
4. [Use Case](#use-case)
5. [Technical Overview](#technical-overview)
6. [Recent Code](#recent-code)
7. [Conclusion](#conclusion)
8. [How to Use](#how-to-use)
9. [License](#license)

---

## Introduction

This Shiny app was created to visualize how tariff adjustments impact the cost and efficiency of sourcing materials from China versus domestic suppliers. It is tailored specifically to **American Plastics Supply & Designer Plastics** as a case study to forecast costs over time with various tariff rates.

---

## Features

- **Forecasting Tool**: Visualize the long-term effects of import and domestic costs over a sliding timeline (6, 12, 18, 24, 48, and 50 months).
- **Dynamic Tariff Adjustments**: Users can input tariff rates to see the impact on costs and tax revenue.
- **Cost Comparison**: Compare the cost of importing acrylic from China versus sourcing domestically.
- **Tax Revenue Insights**: View projected tariff tax revenues and understand their implications.
- **Production Cost Forecasting**: Track domestic production cost projections over time.
- **Export to CSV**: Download adjusted data based on user input for external analysis.
- **Visualization**: Interactive graphs and plots powered by Plotly to animate changes over time.
- **Decision Threshold**: Understand when the cost of importing from China becomes more advantageous compared to domestic sourcing.

---

## Why This Matters

As trade dynamics shift, especially due to tariffs, businesses in the plastics industry face increasing uncertainty. This app helps decision-makers navigate this uncertainty by simulating how different tariff rates and production costs might evolve. James Hartman’s leadership in American Plastics Supply & Designer Plastics demonstrates how adapting to these changes early can provide a significant competitive advantage.

Whether you're managing import and production costs or need to forecast future tax revenues and production costs, understanding the financial implications of your decisions is crucial. With data-driven insights from this app, stakeholders can make informed, confident decisions about sourcing materials and adjusting strategies in the face of trade uncertainties.

---

## Use Case

The app is ideal for business owners, procurement managers, financial analysts, and supply chain experts in industries like plastics manufacturing, where supply chain forecasting is key to staying competitive. By adjusting tariff rates and viewing the impacts over time, users can decide whether importing or sourcing domestically is more profitable at different stages.

For example, James Hartman can use the app to simulate how future tariff adjustments could affect his business's cost structure and tax obligations, helping him make strategic decisions.

---

## Technical Overview

The app is built using **Shiny** in R and utilizes a combination of **ggplot2**, **plotly**, and **DT** to render dynamic graphs and interactive tables. The app's core logic is based on adjusting input data such as tariffs, production costs, and shipping fees over time. The app also includes a CSV export feature for external analysis.

### Key Libraries Used:
- `shiny`: For the web-based interactive application framework.
- `ggplot2` and `plotly`: For creating visualizations.
- `dplyr`: For data manipulation.
- `DT`: For rendering interactive data tables.

---

## Recent Code

```r
# Full R code for the Shiny App (included in previous responses)
```

For the complete source code and deployment instructions, check out the [https://github.com/emcdo411/Hartman-App-Plastics-Supply-Chain-Forecasting/blob/main/README.md](https://github.com/username/Hartman-App-Plastics-Supply-Chain-Forecasting).

---

## Conclusion

The Hartman App offers a powerful tool for analyzing and forecasting the impact of tariffs, costs, and revenues over time. By understanding these key metrics, businesses like **American Plastics Supply & Designer Plastics** can gain a competitive edge in their sourcing decisions. With an easy-to-use interface, real-time data visualizations, and an adjustable framework to simulate different trade conditions, this app empowers decision-makers to take action with confidence.

As trade policies continue to evolve, staying ahead of the curve has never been more important. This app, inspired by the leadership of James Hartman, is an invaluable resource for navigating the shifting tides of global trade.

---

## How to Use

1. Clone or download the repository.
2. Install necessary packages by running:
   ```r
   install.packages(c("shiny", "ggplot2", "plotly", "dplyr", "DT"))
   ```
3. Run the app in RStudio or via the R console using:
   ```r
   shiny::runApp("path_to_the_app_folder")
   ```
4. Adjust the slider for **Projection Timeline** and modify the **Tariff Rate** to simulate different forecasting scenarios.
5. View the graphs, download CSV reports, and analyze how tariffs affect costs, tax revenue, and domestic production.

For the full source code and to access the live app, click [here](https://mmcdonald411.shinyapps.io/HartmanApp/).

---

## License

This app is licensed under the [MIT License](LICENSE). Feel free to contribute or modify it for your own use!

---

With this README structure, the **Hartman App** becomes a versatile, user-friendly tool that is accessible for both technical and non-technical users alike.
