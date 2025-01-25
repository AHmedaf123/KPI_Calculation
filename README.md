KPI Development for Lane Detection Modules
Objective: Define, simulate, and implement Key Performance Indicators (KPIs) for a lane detection module using Python and C++.

Description:
1. Step 1: Research and Define KPIs  
   - Use ChatGPT to identify at least three common KPIs for lane detection (e.g., lane marking accuracy, lane boundary deviation, or detection latency).
   - Summarize the KPIs and explain their relevance in lane detection.

2. Step 2: Simulate Lane Detection Outputs  
   - Write a Python script to simulate lane detection outputs as arrays or JSON data. For example:
     ```json
     {
       "frame": 1,
       "lane_1": {"start": [100, 300], "end": [200, 500]},
       "lane_2": {"start": [300, 300], "end": [400, 500]}
     }
     ```
   - Simulate at least 10 frames with varying lane positions.

3. Step 3: Implement KPI Calculations  
   - Using Python or C++ (their choice), implement functions to calculate the defined KPIs.  
   Example:
     - Lane marking accuracy: Compare simulated lane positions to ground truth.
     - Lane boundary deviation: Calculate the average deviation of detected lanes from expected positions.
