**

## REPEATERS

This python3 program will read a RepeaterBook.com, maybe others, and output a csv file you can use as input for:

* CHIRP - RepeaterBook will do this for you.
* Radioddity GD-88
* (Other Radios?)

The current input varaibles done by editing the code.  These input are:

``` Python
# Look up you Lat/Lon on map.google.com
home = [35.00,-97.00]

# Select the center of you search
center = home

# Range of signals in ??
rang = 50

# What file do you want the output to go to?
input_file = "~/Downloads/repeaterbook_repeaters_.csv"
output_file = "~/Desktop/repeaters.csv"
gd88_output_file = "~/Desktop/gd-88-repeaters.csv"

# what frequency ranges do you want included?
included_frequencies = [[144,148], [420,450]]

# What Modes do you want to exclude?
excluded_modes=['P25','EchoLink', 'IRLP','NXDN','Fusion','DSTAR', 'DMR']
```


**ToDoes**:
Take command line user input.

 - i - input file (default ~/Downloads/repeaterbook_repeaters_.csv)
 - o - output file (default ~/Desktop/<radio>-repeaters.csv)
 - la - latatude
 - lo - longitude
 - r - range from location
 - f = "low,high" frequency range
 - m = mode (analog or digital)
 - R = Radio (<list of here>)
 
Use Repeater Book API to select repeaters.
