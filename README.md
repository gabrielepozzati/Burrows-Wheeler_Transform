# Burrows-Wheeler_Transform
In this implementation I want to allow different kinds of transform by possibly modifying the alphabetical order.

This version of the method may represent a good way to encrypt data. Obviously this is a basic implementation, which is quite useless to encryption purposes. To reach this goal, further modifications will be applied.

Lowercase, uppercase, numbers and basic punctuation are considered in the alphabet which is stored in config.txt file. 
Subsequently, characters which are not present in config.txt should not be present in the input text for the correct execution of the program. New line is allowed in the transform, due to a special treatment.

This code is not yet completely tested for bugs.

These programs require arguments from command line and the config.txt file to be present in the same folder:

$ python bwt.py/lft.py file/text <input_file>/<text_to_transform>






