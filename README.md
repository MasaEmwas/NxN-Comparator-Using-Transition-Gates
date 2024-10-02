# NxN-Comparator-Using-Transition-Gates

This project is a design of an NxN bit comparator using Transmission Gate with the focus on reducing power consumption and propagation delays.

---
### Project Structure
- **ICProjectNEWFINAL.jelib:** Contains all the schematic files and gate symbols for the project.
- **IC_Report.pdf:** A PDF Report
- **README.md:** This file.

--- 
**Note**: The PDF file provides a detailed explanation of the project with figures, tables, graphs and schematic waveforms to represent the results. Furhter, there are many examples with different input data and the corresponding schematic output waveform results. Feel free to refer to it for a more comprehensive understanding of the concepts.

---
### Programs Used:
1. Electric Binary-9.0.7
2. LTspice
---
### How to Use The Project

1. **Download the Project:**
     Clone this repository to your local machine or download the folder.
2. **Download ElectricBinary and LTspice:**
     You will need both programs and the C5_models.txt file (can be found online)
     You may also need the JDK 22.pkg
     
3. **Open Electric Binary-9.0.7:**
     Click **File** --> **Open Library** --> Navigate to the ICProjectNEWFINAL.jelib Project folder and select it.

4. **Update the include Path**
   In your LTspice schematic, locate the line that includes the C5_models.txt file:
   ![here](https://github.com/user-attachments/assets/de83aabb-5b9a-49d1-8dd7-41672a221078)

   Replace /Users/masaemwas/Desktop/ICDownloads/C5_models.txt with the actual path to the location where you saved the C5_models.txt file on your computer. 
