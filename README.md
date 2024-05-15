# EXP.NO:06
# DATE:30/04/2024
# SCHEMATIC ENTRY AND SIMULATION OF CMOS INVERTER, CMOS NAND AND CMOS NOR USING CADENCE TOOL
# AIM:
To design and simulate the CMOS inverter and observe the DC and transient responses using cadence tool.

# APPARATUS REQUIRED:

⦁ Laptop with MobaXterm

⦁ Cadence tool

# PROCEDURE:

# SCHEMATIC ENTRY:

# Creating a new library:

⦁ In the library manager, execute File - New library. The new library form appears. ⦁ In the new library form, type ‘my design lib’ in the name section. ⦁ In the field of directory section, verify that the path to the library is set to ~/Database / Cadence- analog – lab –bl3 and click ok. ⦁ In the next ‘technology file for new library form select option attach to an existing tech file and click ok. ⦁ In the ‘attach design library to technology file’ form, select gpdk045 form the cyclic field and click ok. ⦁ After creating a new library you can verify it from the library manager. ⦁ If you right click on the ‘my design lib’ and select properties, you will find that gpdk045 library is attached as techlib to ‘my design lib’.

# Creating a schematic cell view:

⦁ In the CIW or library manager, execute file – new – cell viw. ⦁ Setup the new file form as follows, Do not edit the library path file and the above might be different from the path shown in your form. ⦁ Click ok when done the above setting. A black schematic window for the inverter design appears.

# Adding components to schematic:

⦁ In the inverter schematic window, click the instance fixed menu icon to display the add instance form. ⦁ Click on the browse button. This opens up a library browser from which you can select components and the symbol view. ⦁ After you complete the add instance form move your cursor to the schematic window and click left to place a component. ⦁ This is a table of components for building the inverter schematic. ⦁ After entering components, click cancel in the add instance form or press ESC with your cursor in the schematic window

![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/8c3a1ebe-b4a6-4b84-9ab8-35ec8e0cd4e9)

# Adding pins to schematic:

⦁ Click the pin fixed menu icon in the schematic window. You can execute create pin or press ‘p’. ⦁ Add pin form appears. Type the following in the ADD pin form in the next order leaving space between the pin. ⦁ Select cancel and then the schematic window enter window file or press the f bind key.

# Adding wires to schematic:

⦁ Click the wire (narrow) icon in the schematic window. ⦁ In the schematic window click on a pin of one of your components as the first point for your wiring. A diamond shape appears over the starting point of this wire. ⦁ Follow the prompts at the bottom of design window and click left on the destination point for your wire. A wire is routed between the source and destination points. ⦁ Complete the wiring as shown in the figure and when done wiring press ECS key in the schematic window to cancel wiring.

# Saving the design:

Click the check and save icon in the schematic editor window observe CIW output for any errors.

# BUILDING THE INVERTER TEST DESIGN:

# Creating the inverter test cell view:

⦁ In the CIW or library manager, execute file – new – cell view. ⦁ Setup the newfile as shown below. ⦁ Click ok when done. A blank schematic window for the inverter test design appears. ⦁ Using the components list and properties/ comments in this table build the inverter test schematic. ⦁ Add the above components using create – instance or by pressing I. ⦁ Click the wire (narrow) icon and wire your schematic. ⦁ Click create wire name or press c to name the i/p (vsin) and output wires as in below schematic. ⦁ Click on the check and save icon to save the design.

![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/7fd55374-b552-4803-8d7c-2ec3af331da6)

# ANALOG SIMULATION WITH SPECTRA:

# Starting the simulation environment:

⦁ In the Inverter-test schematic window execute launch – ADEL. The variable virtuoso analog design environment (ADE) simulation window appears. Choosing a simulator: ⦁ In the simulation window (ADE) execute setup – simulator / directory / host. ⦁ In the choosing simulator form, set the simulator field to specra and click ok. ⦁ In the simulation window (ADE) execute the setup model libraries. To complete, move the cursor and click ok.

# Choosing Analysis:

⦁ Click the choose- Analysis icon in the simulation window (ADE). ⦁ The choosing analysis form appears. ⦁ To Setup the transient analysis. ⦁ In the analysis section select tron. ⦁ Set the stop time as 100ns ⦁ Click at the moderate or enabled button and the bottom and then click apply. ⦁ To set for DC analysis ⦁ In the analysis section select DC. ⦁ Turn on save DC operating point. ⦁ Turn on the component parameters. ⦁ Double click the select Vpulse source or Type V0 (capital V zero). ⦁ Select the DC voltage in the select window parameter and click in the form start and stop voltages are 0 to 1.8. ⦁ Select the enable button and click apply and then click ok.

# Selecting output for plotting:

⦁ Execute the o/p’s to be plotted -select on sschematic in the simulation window. ⦁ Follow the prompt at the bottom. Click on the o/p net vout input vin of the inverter. Press esc with the cursor after selecting.

# Running the simulation:

⦁ Execute the simulation Netlist and run in the simulation window to start the simulation on the icon. This will create the netlist as well as run the simulation. ⦁ When the simulation finishes the transient and DC plots automatically will be popped up along with netlist.

![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/919b125a-4815-4809-b188-f0b3a8b2f273)

![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/3a97599b-2fff-4eac-bff7-ee563d37dda4)

# CMOS NAND GATE NAND SCHEMATIC
![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/84e00c99-b259-4c29-b2fc-af7af3c50ff0)

# NAND TEST CELL VIEW
![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/a0ba7045-c17b-4e38-a9ec-499fe9fff8de)

# NAND SIMULATION WITH SPECTRA
![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/a97f4085-05bf-4896-96b0-5d7fa8e0265f)

# CMOS NOR GATE NOR SCHEMATIC
![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/41387389-7174-436d-9374-47f339f08184)

# NOR TEST CELL VIEW
![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/fd6191c8-2132-4ef4-8eea-c48794a77fce)

# NOR SIMULATION WITH SPECTRA
![image](https://github.com/Pavithra-040404/VLSI-LAB-EXP-6/assets/161431611/01919f00-b94c-4005-be3e-087a754645dd)


# RESULT:

Thus the design and simulation the CMOS inverter and observe the DC and transient responses using cadence tool is verified successfully.










