# api-cloudchannel
How to use Cloud Channel API

## Pre-requisites

### Google WorkSpace User and Role
To API request WORKS a user from Google WorkSpace Domain need to have the Resales permission.


In our case we have created a Google Workspace Custom Function with Resalles read permission. And after it you need to assign this role to Google Workspace user.
![image](https://github.com/user-attachments/assets/372806f8-5529-47ec-83c6-d01af77833af)

![image](https://github.com/user-attachments/assets/4b83905b-3b24-4d79-831e-30c99feb815b)

![image](https://github.com/user-attachments/assets/801a9ad8-a723-4d9c-96ff-3e4c9b77ad98)

![image](https://github.com/user-attachments/assets/a90e3389-35ea-4a0f-a542-3721458e46dc)

![image](https://github.com/user-attachments/assets/1e765bed-520d-4b33-90cc-fc6587d10479)

![image](https://github.com/user-attachments/assets/f0b4bfd8-ce60-49d6-879b-601ccf8fa0ba)


### Service Account

You need to create a service account in your GCP project and get the ID from this account and generate a json key.

![image](https://github.com/user-attachments/assets/d62f7dfb-8615-4f7e-8d53-7564c7eb7830)

After get the Service Account ID go back to google WorkSpace and configure Domain delegate Wide with scope below.

![image](https://github.com/user-attachments/assets/a711c894-4e7f-4357-829c-e819ab0115e1)


https://www.googleapis.com/auth/apps.order


https://www.googleapis.com/auth/cloud-platform

![image](https://github.com/user-attachments/assets/46a17501-30e2-4eef-a756-3dcd08a2f022)


