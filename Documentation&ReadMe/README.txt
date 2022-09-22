To make the microgrid work, you need to ensure that the following two add-ons are installed to your Simulink/MATLAB:

1) This library: https://www.mathworks.com/matlabcentral/fileexchange/67060-systems-level-microgrid-simulation-from-simple-one-line-diagram . You may also be able to find this library using the Add-On Explorer. There’s a demo video for it at https://www.mathworks.com/videos/microgrid-system-development-and-analysis-part-3-using-simscape-power-systems-to-simulate-microgrids-1522853406434.html .

2) Simscape Electrical Toolbox. You should be able to find this in the Add-On Explorer.

---

If significant errors occur when opening the model, check to make sure that the location where you saved the model and the associated files is added to the MATLAB path or the folder is open in MATLAB. Press the "run" command in Simulink once you have updated the folders. If problems persist, ensure that you have the proper add-ons installed, as described earlier in this readme.

---

To return to the main menu of the model, click on the "UREC_microgrid" tab located on the top left of the main screen. Depending on where you've currently navigated to, it may look like "UREC_microgrid > Battery Logic..." or "UREC_microgrid > USER INTERFACE:..."
