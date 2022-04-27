<h1 align="center"> GNC Labeling Process</h1>

 https://www.gnc.com/proaccess is a website hosted and managed by Bulu to support the GNC Pro Access program. The website was created in march of 2017 and funded by  GNC enterprise. The website contains a historical record of each PRO Access member’s PRO Box history. This record allows Bulu to create labels for each subscription box. The GNC labeling process can be ccategorized in the following steps:
 
## Step 1
**GNC:** The GNC’s customer relationship management (CRM) team determines which customers are to be included in this quarter’s direct to customer (D2C) mailing list. This information may include: address validation, customer communication emails, reassigning customers to different cohorts etc. GNC then sends a direct file transfer of the Customer Data File (CDF)through Acxiom to Bulu using a SFTP Protocal. SFTP stands for SSH (or Secure) File Transfer Protocol, which usually runs on Port 22. SFTP is used to transferring files between client and server over a Secure and Encrypted Connection [1].

## Step 2
**BULU:** Bulu retrieves the customer data file (CDF), and assigns each customer a Box ID based on the customer’s box type preference, customer’s sample choice selection, and available inventory. The Bulu experts than run the customer data file (CDF) through the carrier’s API to generate a tracking number. Bulu then creates a zebra programming file (ZPL) [2] of the shipping label and creates a SKU code, and manually fixes the package’s endorsement. Bulu prints the shipping labels, this process can take several days to complete depending on the quantity of direct to customer(D2C) shipments. Bulu then applies the shipping labels to pre-kitted boxes or directly to boxes as there are being kitted. Bulu then palletizes labeled PRO Boxes in batches of 600-750 (depending on weight of box), which will be ready for shipment

## Step 3
**DHL:** N/A

Below is a detailed illustration of how GNC labels process function operates from start point to end point. The diagram design is a detailed structure of Bulu’s, GNC and DHL architecture structure and mechanism. The diagram helps us accumulated the different stages of the labeling process and gives a detailed analysis of every step of GNC labeling Process. For more information on the GNC labeling diagram [3]

![](https://github.com/BuluBoxSoftware/Documentation/blob/main/GNC/Diagram.png)

## Summary
This mechanism allows us to pin point what exact process is being executed in the hierarchy of the diagram. The process starts on the upper left corner labeled customers. The customers enroll in GNC Pro program website. They are placed in a cohort based on:<br> 
 <ul>
  <li>Data of sign up</li>
  <li>Box type</li>
</ul>  

The GNC environment then determines the cohorts. GNC sends Bulu a customer data file in CSV [4] format. It contains personal information on the customer which includes email, address, box choice etc. They send the file using STFP protocol. Bulu then provide headers for each field in the files. The CSV file includes the box type assigned to that customer and a sample for customer sample choice. Bulu then assigns a box ID and SKU to track each box.  SKU stands for stock-keeping unit, which is a scannable bar code, printed on product labels. The label allows vendors to automatically track the movement of inventory. SKU is composed of an alphanumeric combination of eight characters [5]. This process is done using ZPL extension files to generate the tracking number. Once’s this process is complete printing and pre kitting process is undertaken, this particular process can take up to several days to complete depending on the quantity of the direct to customer (D2C) shipments. Lastly palletizes and wrapping is done for the final box product to be shipped.

## References

[1] https://www.pcwdld.com/what-is-sftp-and-port-number#wbounce-modal<br>
[2] https://github.com/BuluBoxSoftware/Documentation/tree/main/ZPL<br>
[3] https://lucid.app/lucidchart/19faa4a8-3f01-4ffd-9da5-ecf9060c62cc/edit?beaconFlowId=89F21EB96A193A15&invitationId=inv_2d8eed7f-ca8c-483d-808c-78b627f5b9b5&page=0_0#<br>
[4] https://support.google.com/google-ads/answer/9004364?hl=en<br>
[5] https://www.brightpearl.com/ecommerce-guides/understanding-skus

<h5 align="center"> Copyright (C) 2022 by BuluBox. All rights reserved</h5>
