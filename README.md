# 📊 Engineering Economics Analysis Tool
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Tool](https://img.shields.io/badge/Tool-MATLAB%20App%20Designer-blue?style=for-the-badge&logo=mathworks&logoColor=white)

This repository contains a sophisticated graphical user interface (GUI) developed using **MATLAB App Designer** for performing a wide range of engineering economics calculations. The application provides an interactive and real-time environment for financial analysis, designed to simplify complex calculations for engineers and financial analysts.

This project was developed for the Engineering Economics course taught by Dr. Nozarian.

## ✨ Key Features

This application is packed with features that provide a seamless and intuitive user experience:

* 💰 **Real-Time Economic Analysis**: Instantly calculates and displays key economic indicators including **Net Present Worth (NPW)**, **Net Equivalent Uniform Annual (NEUA)**, and **Net Future Worth (NFW)** as you adjust input parameters.
* 📉 **Dynamic Cash Flow Diagram**: Automatically generates and updates a **cash flow diagram** in real-time, providing an immediate visual representation of the project's finances.
* ⚙️ **Multiple Depreciation Methods**: Calculates depreciation ($D_m$) and book value ($BV_m$) for any given year (`m`) using three standard methods:
    * **SL** (Straight-Line)
    * **SOYD** (Sum-of-the-Years'-Digits)
    * **DB** (Declining Balance)
* 💸 **Progressive Tax Calculation**: Features a flexible tax calculation module based on a progressive, three-bracket tax system. Users can define the income brackets and their corresponding tax rates to compute the tax liability for any year.
* 📈 **Sensitivity Analysis**: Generates a "spider plot" to visualize the sensitivity of the project's **NPW** to percentage changes in key variables (Initial Investment, Annual Revenue, Gradient, Salvage Value, MARR, and Number of Periods).
* 🎨 **Interactive & User-Friendly GUI**:
    * All input parameters, such as initial investment, annual revenue, MARR, and salvage value, can be adjusted using intuitive **sliders or by typing values directly**.
    * The application features a custom-designed logo, a loading screen, and helpful **tooltips** for all interactive elements to guide the user.

## 🚀 How to Run the Application

1.  Ensure you have **MATLAB** installed (the application was developed on a recent version with App Designer).
2.  Download the `app1.mlapp` file from this repository.
3.  Open the `app1.mlapp` file in MATLAB. This will launch the **App Designer** interface.
4.  Click the **"Run"** button in the App Designer toolstrip to start the application.

## ✍️ Author
* **Ali Naghiloo**

---
*This project is for educational purposes and is licensed under the MIT License.*
