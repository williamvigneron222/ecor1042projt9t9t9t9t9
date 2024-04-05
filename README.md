# Interactive Character Information Retrieval Program
 #### Date: April 10th, 2024
 #### Software: Python 3.11.7 
 #### Contact Information: 
-  __Team Leader__ – Julia Hanlon
 
-  __Email__ - juliahanlon@cmail.carleton.ca

## Description:
The interactive program allows the user to load data from a given file that the user inputs and then you can sort the data, find a best fitting line that goes through the existing data or create a histogram. The batch UI provides the same functionality, the program intakes a text file containing batch commands and outputs the desired function.

## Dependencies:
- [Python 3.11.7](https://www.python.org/downloads/release/python-3117/)
- [matplotlib.pyplot](https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html)
- [Numpy](https://numpy.org/)

## Installation:

### __Install Python 3.11.7:__
#### For Windows and Mac OS:
1. Go to the [Python official website](https://www.python.org/downloads/release/python-3117/) and download the installer package. Mac OS has a specific package that should only be used for Mac OS and Windows has a variety of packages.
2. Find the release version ‘Python 3.11.7’ and download. Once downloaded, follow any further setup instructions.

### __Install Pip, Matplotlib, and Numpy:__ 
_(ref. ECOR 1042 Data Management, “Installing Matplotlib, NumPy, and SciPy”, Carleton University):_
#### For Windows:
1.	To install pip, type the following command in the desktop terminal. This will install pip if it hasn’t already been installed with the python installation. 
`python -m ensurepip`
2.	To install Matplotlib, type the following command in the desktop terminal.
`python -m pip install matplotlib`
3.	To install NumPy, type the following command in the desktop terminal.
`python -m pip install numpy`

#### For Mac OS:
1.	To install, type the following command in the desktop terminal. This will install pip if it hasn’t already been installed with the python installation. 
`$ python3 -m ensurepip`
2.	To install Matplotlib, type the following command in the desktop terminal.
`$ python3 -m pip install matplotlib`
3.	To install NumPy, type the following command in the desktop terminal. 
`$ python3 -m pip install numpy`

### __Project Installation:__
Once the libraries are installed, extract the python files from the .zip file. Open the `batch_UI.py` or `text_UI.py` module to use the program. Ensure all files remain in the same folder.




## Credits:
### Julia:
- `character_weapon_list` function
- `test_return_list_correct_length` function
- `sort_characters_intelligence_selection` function
- `histogram` function

### Blayke:
- `character_occupation_list` function
- `calculate_health` function
- `test_return_list` function
- `sort_characters_health_insertion` function
- `batch_ui` module

### Alex:
- `character_luck_list` function
- `test_calculate_health` function
- `sort_characters_agility_bubble` function
- `text_ui` module

### William:
- `character_strength_list` function
- `load_data` function
- `test_return_correct_dict_inside_list` function
- `sort_characters_armor_bubble` function
- `curve_fit` function

## Usage: 
Please refer to the user video provided to find detailed instructions on the use of this program.

## License: 
MIT License

Copyright (c) 2024 Julia Hanlon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
