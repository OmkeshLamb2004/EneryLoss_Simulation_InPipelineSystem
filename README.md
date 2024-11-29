# Advanced Pipeline Analysis Calculator  

## Description  
The **Advanced Pipeline Analysis Calculator** is a Python-based tool designed for engineers and fluid mechanics enthusiasts to calculate and analyze pipeline parameters like pressure loss, energy loss, velocity changes, and friction factors. This application uses scientific methods and a GUI (Graphical User Interface) built with **Tkinter** for an intuitive user experience. It also generates detailed visual plots for a comprehensive understanding of pipeline dynamics.

## Features  
- **Input Parameters:** Easily input pipe dimensions, fluid properties, and environmental conditions.  
- **Material Options:** Supports common pipe materials like Steel, PVC, Copper, and more.  
- **Dynamic Calculations:** Iterative analysis for Reynolds number, friction factor, and pressure losses.  
- **Real-Time Feedback:** View progress in the text log window during calculations.  
- **Graphical Outputs:** Plots for pressure loss, energy loss, velocity, and more.  
- **Adjustable Parameters:** Customize number of bends and other pipeline characteristics.  
- **Error Handling:** Robust input validation and error messaging.  

## Prerequisites  
Ensure the following libraries are installed before running the project:  
- `numpy`  
- `matplotlib`  
- `scipy`  
- `tkinter` (included with Python)  

Install dependencies using pip:  
```bash
pip install numpy matplotlib scipy
```

## Usage  
1. Clone this repository:  
   ```bash
   git clone https:https://github.com/OmkeshLamb2004/EneryLoss_Simulation_InPipelineSystem.git
   cd EneryLoss_Simulation_InPipelineSystem

   ```  
2. Run the application:  
   ```bash
   python EneryLoss_Simulation_InPipelineSystem
   ```  
3. Input the required parameters in the GUI:  
   - Pipe length, diameter, material, etc.  
   - Choose the number of bends and adjust elevation changes.  
4. Click **"Calculate"** to analyze.  
5. View graphical outputs in the right panel and detailed results in the text log.

## Output Graphs  
- **Pressure Loss Profile:** Pressure drop along the pipe length.  
- **Energy Loss Profile:** Visualization of energy losses.  
- **Velocity Profile:** Fluid velocity changes over the pipeline.  

## Files  
- `pipeline_analyzer.py`: Main program file.  
- `pipeline_analyzer.log`: Log file for recording calculation steps and issues.  
- `README.md`: Documentation.  

## Contributions  
Contributions are welcome!  
1. Fork this repository.  
2. Create a new feature branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Add new feature"  
   ```  
4. Push the branch and open a Pull Request.  

## License  
This project is licensed under the MIT License.  

## Screenshots  
Here is a screenshot of the application:

![Screenshot](https://raw.githubusercontent.com/OmkeshLamb2004/EneryLoss_Simulation_InPipelineSystem/main/Screenshot%202024-11-27%20232023.png)


---  
Developed with ❤️ by [Omkesh Lamb](https://github.com/<OmkeshLamb2004>)  
Feel free to contribute, raise issues, or suggest features!  
