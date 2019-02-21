# p2x
A tool which can generate equivalent XML(tag based) code for the given Python Code. 
p2x has been developed by updating the tree generation process of lark parser. 
python3.lark contains the grammar of python3, which can be parsed by the lark parser. 
Some new productions has been added in the grammar file. 
You can use it for XML based equivalent code of python.
We have just perform some updations as mentioned above in the lark parser code taken from the web resource: https://github.com/lark-parser/

Installation Process:

Require python 3.5 or above.

1. Clone or Download from the Github.
2. Unzip the folder.
3. From the ternimal
   3.1 Jump to the p2x folder
   3.2 pip install Updated_lark.zip  #Install Updated Lark Parser. Have a look at https://github.com/lark-parser/ for more information.
   3.3 Now lark is installed.
   3.4 test.py file is given which contains example python code.
   3.5 How to Run: python demo.py test.py xml_data.xml
   # XML generated code saved into xml_data.xml file. Open the xml file in web browser for better visualization.
   # Based on requirement change the demo file.
   
   
