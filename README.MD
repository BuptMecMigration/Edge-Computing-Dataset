# About Edge Computing Dataset

This dataset is from ISP in china and is publicly released for researches in Edge Computing. The dataset not only contains base station location and user access time,  **but also records URLs, server ports and gateway IP for service/applications, which are important for edge computing researches. ** 

# Analysis of Telecom Dataset

The following figures show some statistical results obtained from the dataset. 

The average number of requests sent by each user in the month is shown in Figure 1. 

![image-20220514163420339](image/image-20220514163420339.png)

In Figure 2, the requests are classified into four categories according to their duration.

![image-20220514163444925](image/image-20220514163444925.png)

# Parameter Description

This dataset provides over 480,000 records of mobile users through 16,000 base stations from Beijing, Shanghai and Guangzhou.  The parameters and their descriptions are listed in the following table. The URL field of some records is vacant because it is a https link. In order to protect user privacy, some sensitive information has been processed.

| ID  | Parameter Name   | Description                                                        |
|:---:|:----------------:|:------------------------------------------------------------------:|
| 1   | Phone Number     | Encrypted phone number                                             |
| 2   | LAC              | Location Area Code                                                 |
| 3   | CI               | Cell Identification                                                |
| 4   | APN              | Access Point Name                                                  |
| 5   | IMEI             | International Mobile Device Identifier                             |
| 6   | SGSN IP          | The recording of the location information of the record            |
| 7   | GGSN IP          | For the interaction between different data networks                |
| 8   | Start Time       | The time when a record starts                                      |
| 9   | End Time         | The time when a record ends                                        |
| 10  | Duration         | The duration of the record                                         |
| 11  | Uplink traffic   | The number of bytes sent by the record to the destination          |
| 12  | Downlink traffic | The number of bytes the record has downloaded from the destination |
| 13  | RAT Type         | The radio access type of one record                                |
| 14  | Source IP        | The IP of the source                                               |
| 15  | Source Port      | The port of the source                                             |
| 16  | Destination IP   | The IP of the destination                                          |
| 17  | Destination Port | The port of the destination                                        |
| 18  | Status Code      | The state code of HTTP                                             |
| 19  | URL              | The url that one record visits                                     |
| 20  | User Agent       | The record of the access method of one record                      |
| 21  | Content-Type     | The media information of one record                                |
| 22  | Date             | The date of one record                                             |

# Dataset Citation

If you have used the dataset, we would appreciate citations to the following paper:

- Haojiang Liu, Yuanzhe Li, Shangguang Wang. Request Scheduling Combined with Load Balancing in Mobile Edge Computing. IEEE Internet of Things Journal, 2022
