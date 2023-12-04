

# Paragraph Justification Program

This Python program accepts a paragraph string and a page width as parameters and returns an array of left-justified and right-justified strings without breaking words.

## How to Execute the Program

1. Clone the repository or download the 'Final-Gspann_V3' file/folder.

2. Make sure you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).

3. Open your terminal or command prompt.

4. Navigate to the directory where 'version3.py' is located.

5. Run the program by executing the following command:


   python Final-Gspann_V3.py
   
   
### Sample Output 01

#### user input
Enter the paragraph: This is a sample text but a complicated problem to be solved, so we are adding more text to see that it actually works.

Enter the page width: 20

#### system output
Array[1] = "This   is  a  sample"\
Array[2] = "text      but      a"\
Array[3] = "complicated  problem"\
Array[4] = "to  be solved, so we"\
Array[5] = "are adding more text"\
Array[6] = "to   see   that   it"\
Array[7] = "actually      works."\"


#### sample output 02

#### user input
Enter the paragraph:  _do not provide the first input_. Click RETURN/ENTER.
--> When the input prompt re-appears provide a valid string.

Enter the paragraph: This Python program accepts a paragraph string and a page width as parameters and returns an array of left-justified and right-justified strings without breaking words.

Enter the page width:  _do not provide the first input_. Click RETURN/ENTER.
--> When the input prompt re-appears provide a valid integer.

Enter the page width: 20


#### system output
A paragraph Input is skipped: Paragraph should be a non-empty string.
A page width Input is skipped: invalid literal for int() with base 10:
Array[1] = ""This Python program"\
Array[2] = "accepts  a paragraph"\
Array[3] = "string  and  a  page"\
Array[4] = "width  as parameters"\
Array[5] = "and returns an array"\
Array[6] = "of    left-justified"\
Array[7] = "and  right-justified"\
Array[8] = "strings      without"\
Array[9] = "breaking     words."
