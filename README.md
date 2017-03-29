# Fileman-Delphi-Components-FMDC-
File-man Delphi Components or FMDC Components

I will guide you step by step while configuring FMDC code. I tested, installed and fixed code, path, and components using RAD Berlin 10.1 and RAD Tokyo 10.2. It should work with prior versions of Delphi Studios (Borland etc.) with some configuration changes.

Code Setup Instructions:

Note: Throughout these instructions do not forget to keep saving the projects before closing after 'successful' builds or installs. Feel free to delete Project files; package compile and build will generate new itself. You can always check successful installed components by clicking "Components -> Installed Packages" on main menu bar. Scroll all the way down to see or find your package name(s) here. In this case you will be able to see component name as 'Vista Fileman Delphi Components'

FMDC

Pre-Requisite: Broker Component XWB_RXE3 and XWB_DXE3. I am attaching this broker source in a zip file too. But if you have some other version of broker installed just change 'requires' to your installed broker version and it should work.

Step 1: Open FMDC Delphi Package. Right Click on FMDC Project and click on Options and set 'DCP Output Directory' and 'Unit Output Directory' to '[Your Directory]\FMDC\Driver\DCU\
Step 2: Right click on project and click ‘Clean’, ‘Compile’ and then ‘Build’. An extra step here would be right click again and now ‘Install’. It should display the following message in the pop-up "Package [Directory Path] has been installed. The following new component(s) have been registered: TFMCheckBox, TFMComboBox, TFMComboBoxLookUp, TFMEdit, TFMFiler, TFMFinder, TFMFindOne, TFMGets, TFMHelp, TFMLabel, TFMListBox, TFMLister, TFMLookUp, TFMMemo, TFMRadioButton, TFMRadioGroup, TFMValidator."
