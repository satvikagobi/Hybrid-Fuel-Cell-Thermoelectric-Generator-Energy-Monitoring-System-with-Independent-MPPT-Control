# Hybrid-Fuel-Cell-Thermoelectric-Generator-Energy-Monitoring-System-with-Independent-MPPT-Control

Designed and simulated a **hybrid renewable energy system** in **MATLAB Simulink** by integrating a **Fuel Cell (FC)** and a **Thermoelectric Generator (TEG)** as two independent energy sources. Each subsystem was equipped with a dedicated **Perturb and Observe (P&O) Maximum Power Point Tracking (MPPT)** controller implemented using MATLAB Function blocks, enabling continuous tracking of the maximum power operating point under varying source conditions. The MPPT controllers generated optimized duty cycles to drive independent **DC-DC boost converters**, ensuring efficient voltage enhancement and maximum power extraction from both renewable sources.

The Fuel Cell subsystem converts the chemical energy of hydrogen into electrical energy, while the Thermoelectric Generator utilizes the **Seebeck effect** to convert waste heat into usable electrical power. Independent voltage and current measurement blocks were incorporated into each subsystem to continuously monitor electrical parameters. The instantaneous output power of each source was calculated in real time using (P = V \times I), providing accurate performance evaluation throughout the simulation.

To integrate the two renewable sources without directly combining their electrical outputs, an intelligent **Energy Monitoring and Source Identification System** was developed. The calculated power outputs of the Fuel Cell and TEG were continuously compared using comparison logic implemented in Simulink. Based on the real-time power values, the system automatically identified the dominant energy source and displayed its status, providing a simple yet effective energy management framework while maintaining complete electrical independence between the two sources.

The project demonstrates the practical implementation of **renewable energy integration, MPPT-based power optimization, DC-DC boost converter design, real-time power measurement, and intelligent energy monitoring** within a single hybrid energy platform. By combining independent source optimization with continuous performance analysis, the proposed system improves energy utilization, simplifies hybrid source management, and provides a scalable foundation for future enhancements such as battery energy storage, bidirectional power converters, advanced energy management algorithms, SCADA-based monitoring, IoT connectivity, and hybrid electric vehicle applications.

**Technologies & Skills:** MATLAB Simulink, MATLAB Function Blocks, Fuel Cell Modeling, Thermoelectric Generator (TEG), Perturb & Observe (P&O) MPPT, DC-DC Boost Converters, PWM Control, Power Electronics, Renewable Energy Systems, Hybrid Energy Systems, Real-Time Power Monitoring, Energy Management, Voltage and Current Measurement, Source Identification, Sustainable Energy Technologies.

---

## Author

**Satvika Gobi**


