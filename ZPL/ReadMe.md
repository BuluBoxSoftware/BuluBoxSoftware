# Zebra programming Language 

**What is ZPL (Zebra programming Language)?**

It is the command based programming language used by the printers as instructions to create the images printed on the labels.

**Why is the ZPL (Zebra programming Language important)?**

This specific program allows us to create barcodes , text and number code with ZPL 
Zebra programming Language extension is .ZPL

**How does ZPl (Zebra programming Language work) ?**

* Here are some examples to practice and get familiar with ZPl (Zebra programming Language work): **http://labelary.com/viewer.html**
* ZPL official manual guide: **https://www.zebra.com/content/dam/zebra_new_ia/en-us/manuals/printers/common/programming/zpl-zbi2-pm-en.pdf**

------------------------------------------------------

**Code Example**

^XA Code Begins <br>
^FX Top section with logo, name and address.<br>
^CF0,60<br>
^FO50,50^GB100,100,100^FS<br>
^FO75,75^FR^GB100,100,100^FS<br>
^FO93,93^GB40,40,40^FS<br>
^FO220,50^FD BULU BOX^FS<br>
^CF0,30<br>
^FO220,115^FD4000 Products^FS <br>
^FO220,155^FD5240 S 19th St, Lincoln, NE 68512^FS<br>
^FO220,195^FDUnited States (USA)^FS <br>
^FO50,250^GB700,3,3^FS <br>

^FX Second section with recipient address and permit information.<br>
^CFA,30 <br>
^FO50,300^FDMarcus Quevedo^FS <br>
^FO50,340^FD6001 Dodge St^FS <br>
^FO50,380^FDOmaha, NE 68182^FS <br>
^FO50,420^FDUnited States (USA)^FS <br>
^CFA,15 <br>
^FO600,300^GB150,150,3^FS <br>
^FO638,340^FDPermit^FS <br>
^FO638,390^FD123456^FS <br>
^FO50,500^GB700,3,3^FS <br>

^FX Third section with barcode.<br>
^BY5,2,270 <br>
^FO100,550^BC^FD12345678^FS <br>

^FX Fourth section (the two boxes on the bottom). <br>
^FO50,900^GB700,250,3^FS <br>
^FO400,900^GB3,250,3^FS <br>
^CF0,40 <br>
^FO100,960^FDCtr. X34B-1^FS <br>
^FO100,1010^FDREF1 BAY1^FS <br>
^FO100,1060^FDREF2 BAY2^FS <br>
^CF0,190 <br>
^FO470,955^FDNE^FS <br>
^XZ Code Ends <br>

---------------------------------------------------

**Result**

![](ZPL.png)

----------------------------------------------------
**References**

1. https://www.zebra.com/us/en/support-downloads/knowledge-articles/ait/View-content-of-stored-ZPL-file-in-printer.html
2. http://labelary.com/viewer.html
3. https://www.zebra.com/content/dam/zebra_new_ia/en-us/manuals/printers/common/programming/zpl-zbi2-pm-en.pdf

<h5 align="center"> Copyright (C) 2022 by BuluBox. All rights reserved</h5>
