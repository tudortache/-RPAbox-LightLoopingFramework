# -RPAbox-LightLoopingFramework


A very light version of a framework for implementations. Additionally, you can use this as a repetitive subcomponent of 
your process due to the small footprint. Regardless of your choice, you will need to change just a few things in order 
to get started. 



Where to look for changes:
 
 - Change the Variable Type for <tranzactionItem> and <tranzactionItems> to suit your needs. Make sure the latter is an 
array of the former, otherwise additional changes will be required.
 
- Fill in the actual process steps in these files - LoginApp1.xaml, Process.xaml, KillAllProcesses.xaml and, optionally HandleErrorsApp1.xaml.

 - Add process specific settings in the Config file, then grab them from the <config> variable in order to pass them as arguments mainly to Process.xaml.