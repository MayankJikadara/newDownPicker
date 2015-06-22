# newDownPicker
Down Picker for iOS apps ( Picks from a list of several options )

Hello I am Karan Singh and is a down picker improvement over basic;

Please feel free to comment of improve the solution -

Objective - Change your textfield to DownPicker


INITIALIZE - 
1) Drag and drop the down picker folder into your project.
2) import the headerfile in the view controller .  (#import "DownPicker.h")
3) Define a global variable of class DownPicker.   (@property (strong,nonatomic) DownPicker *downPicker;)
4) Just add a line to the viewDidLoad method with the array of strings and target text field  (self.downPicker = [[DownPicker alloc]initWithTextField:self.textField withData:array withPlaceholder:@"SELECT COUNTRIES"];)


See the sample for more details
