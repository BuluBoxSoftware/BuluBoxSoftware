# GNC Lables Process

**Step 1**:
The GNC’s Customer relationship management (CRM) team determines which customers are to be included in this quarter’s direct to Customer Mailing (D2C) mailing list.
This includes steps like: **address validation, customer communication emails, reassigning customers to different cohorts.** 

**Step 2**:
GNC sends Bulu which is our portal webiste the Customer Data File (CDF) via the SFTP. The SFTP port number is SSH port 22.

----------------------------------------------

**Step 3**:
Bulu retrieves the  Customer Data File (CDF), and assigns each customer a Box ID based on the customer’s **box type preference, the customer’s sample choice selection, and available inventory**.

**Step 4**:
Bulu runs the Customer Data File (CDF)  through the carrier’s  application programming interface (API) to generate a tracking number. 

**Step 5**:
Bulu creates a Zebra Programming Langhuange (ZPL) file of the shipping label, and manually fixes the package’s endorsement.

**Step 5**:
Bulu prints the shipping labels. Depending on the quantity of direct to customer mailing (D2C) shipments, this  step can can take several days to complete . 

