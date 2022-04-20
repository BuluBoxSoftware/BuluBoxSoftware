# GNC Lables Process

**Over view:** The GNC labeling process can be catogorized in the following main steps:


## Step 1

**GNC:** The GNC’s CRM Team determines which customers are to be included in this quarter’s D2C mailing list.This information may include: address validation, customer communication emails, reassigning customers to different cohorts etc. GNC then sends Bulu API server the Customer Data File (CDF) via the SFTP. SFTP stands for SSH (or Secure) File Transfer Protocol, which usually runs on Port 22. SFTP is used to transferring files between client and server over a Secure and Encrypted Connection [1].

## Step 2

**BULU:** Bulu retrieves the customer data file (CDF), and assigns each customer a Box ID based on the customer’s box type preference, customer’s sample choice selection, and available inventory. The Bulu experts than run the customer data file (CDF) through the carrier’s API to generate a tracking number. Bulu creates a ZPL file of the shipping label, and manually fixes the package’s endorsement (this may be unique to FedEx). Bulu prints the shipping labels. Depending on the quantity of D2C shipments, this can take place over several days. Bulu prints the shipping labels. Depending on the quantity of D2C shipments, this can take place over several days. Bulu applies shipping labels to pre-kitted boxes or directly to boxes as they are being kitted. Bulu palletizes labeled PRO Boxes in batches of 750.Bulu may load fewer boxes/pallet depending on the weight of the box. Bulu schedules carrier pickups by the trailer load. Typically, an empty trailer is left at Bulu while a full trailer is picked up. Boxes are NOT tracked by trailer load. 


## Step 3

 

**DHL:**

 --------------------------
 
**Diagram:**



The following diagram can be viewd [3].

**Summary**
 
---------------------------------------------
**Refrences:**

[1] https://www.pcwdld.com/what-is-sftp-and-port-number#wbounce-modal<br>
[2]<br>
[3] https://lucid.app/lucidchart/19faa4a8-3f01-4ffd-9da5-ecf9060c62cc/edit?beaconFlowId=89F21EB96A193A15&invitationId=inv_2d8eed7f-ca8c-483d-808c-78b627f5b9b5&page=0_0#
