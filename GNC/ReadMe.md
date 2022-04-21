<h1 align="center">GNC Labeling Process</h1>

 https://www.gnc.com/proaccess is a website hosted and managed by Bulu to support the GNC Pro Access program. The website contains a historical record of each PRO Access member’s PRO Box history.The GNC labeling process can be catogorized in the following  three main steps:
 
## Step 1

**GNC:** The GNC’s customer relationship management (CRM) team determines which customers are to be included in this quarter’s direct to customer (D2C) mailing list. This information may include: address validation, customer communication emails, reassigning customers to different cohorts etc. GNC then sends Bulu API server the Customer Data File (CDF) via the SFTP. SFTP stands for SSH (or Secure) File Transfer Protocol, which usually runs on Port 22. SFTP is used to transferring files between client and server over a Secure and Encrypted Connection [1].

## Step 2

**BULU:** Bulu retrieves the customer data file (CDF), and assigns each customer a Box ID based on the customer’s box type preference, customer’s sample choice selection, and available inventory. The Bulu experts than run the customer data file (CDF) through the carrier’s API to generate a tracking number. Bulu then creates a zebra programming file (ZPL) [2] of the shipping label, and manually fixes the package’s endorsement. Bulu prints the shipping labels, this process can take several days to complete depending on the quantity of direct to customer(D2C) shipments. Bulu then prints the shipping labels depending on the quantity of  direct to customer (D2C) shipments, the process can take up to severla days to complete. Bulu applies shipping labels to pre-kitted boxes or directly to boxes as there are being kitted. Bulu then palletizes labeled PRO Boxes in batches of 750 , which will be ready for shipment.

## Step 3

**DHL:**


 




The following diagram can be viewd here [3].

**Summary:**
Below is a detailed illustration of how GNC labels process function operates from start point to end point. The diagram design is a detailed structure of Bulu’s, GNC and DHL architecture structure and mechanism.

![]()




This mechanism allows us to pin point what exact process is being executed in the higharky of the diagram. The process starts on the upper left corner labeled Customers and     

---------------------------------------------
**Refrences:**

[1] https://www.pcwdld.com/what-is-sftp-and-port-number#wbounce-modal<br>
[2] https://github.com/BuluBoxSoftware/Documentation/tree/main/ZPL<br>
[3] https://lucid.app/lucidchart/19faa4a8-3f01-4ffd-9da5-ecf9060c62cc/edit?beaconFlowId=89F21EB96A193A15&invitationId=inv_2d8eed7f-ca8c-483d-808c-78b627f5b9b5&page=0_0#<br>
[4]<br>
[5]

<h5 align="center"> Copyright (C) 2022 by BuluBox. All rights reserved</h5>
