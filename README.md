Project Description:
   This project is a simulation of the Tandem t:slim X2 Insulin Pump. The simulation demonstates the key features of the pump including:
      - Insulin Delivery: Both basal and bolus insulin injections
      - ControlIQ: Adjusts insulin delivery based on continuous glucose monitoring (CGM) data
      - Profile Management: CRUD system for managing personal insulin delivery profiles (basal rates, carb ratio, correction factor, target glucose)
      - Monitoring and Logging: Real-time feedback on battery status, insulin levels, Insulin on Board (IOB) and glucose levels; logging of events and error handling
      - Timing: CGM measurements occur every 5 real seconds at 30 minute simulation intervals. 1 real second is equivalent to 6 simulated minutes.

Instructions on how to run:
   1. Open terminal and run these commands to install QTCharts:
         - sudo apt update
         - sudo apt install libqt5charts5-dev
   2. Open the project in Qt (using .pro file).
   3. When prompted to enter PIN, enter 1234 (PIN is hardcoded).
  
