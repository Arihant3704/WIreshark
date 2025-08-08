# WIreshark


## 1. What is the 48-bit Ethernet address of your computer?
### Ans:- 00:80:ad:73:8d:ce
<img width="1920" height="1080" alt="question123" src="https://github.com/user-attachments/assets/bdc8dae3-1b83-46be-b48e-e6213b003882" />

## 2. What is the 48-bit destination address in the Ethernet frame? Is this the Ethernet address of gaia.cs.umass.edu? (Hint: the answer is no). What device has this as its Ethernet address? [Note: this is an important question, and one that students sometimes get wrong. Re-readipages 468-469 in the text and make sure you understand the answer here.]
### Ans:-00:06:25:da:af:73

## 3. Give the hexadecimal value for the two-byte Frame type field. What upper layer protocol does this correspond to?
### Ans:- IPV4 (0X0800)

<img width="1920" height="1080" alt="Screenshot from 2025-07-30 11-37-48" src="https://github.com/user-attachments/assets/34e7ac8b-13f5-40bd-a18b-21c15b91c5ed" />

## 4. How many bytes from the very start of the Ethernet frame does the ASCII "G" in "GET" appear in the Ethernet frame? Net answer the following questions based on the contents of the Ethemet frame?
### Ans:- 47 byte  (54-56 byte)


# AGU 8 2025
## 5. What are the SSIDs of the two access points that are issuing most of the beacon frames in this trace? 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/60e6cff6-5e4c-42e4-ba55-ea36aa8ee377" />

### Ans:-The two access points broadcasting the most beacon frames in this trace have the SSIDs "30 Munroe St" and "linksys_SES_24086". Some sources may also refer to the "linksys_SES_24086" SSID simply as "linksys12"



## 6 What are the intervals of time between the transmissions of the beacon frames the  linksys_ses_24086 access point? From the 30 Munroe St. access point? (Hint: this interval of time is contained in the beacon frame itself).

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4654dffc-2fca-4373-ae03-e35ed923c72c" />

### Ans:- 102.4 milliseconds  (The interval of time between beacon frame transmissions from both the Linksys_SES_24086 access point and the 30 Munroe St. access point is typically 0.1024 seconds (or 102.4 milliseconds). This interval, known as the beacon interval, is a configurable parameter on most access points and is expressed in Time Units (TU). One TU equals 1024 microseconds or 1.024 milliseconds.)


## 7 What (in hexadecimal notation) is the source MAC address on the beacon frame from 30 Munroe St? Recall from Figure 7.13 in the text that the source, destination, and BSS are three addresses used in an 802.11 frame. For a detailed discussion of the 802.11 frame structure, see section 7 in the IEEE 802.11 standards document (cited above).

<img width="940" height="462" alt="image" src="https://github.com/user-attachments/assets/2bab8dec-7e16-44d2-8991-391b8ba60dc6" />

### Ans:-Source address: Cisco-Li_f7:1d:51 (00:16:b6:f7:1d:51)

## 8  . What (in hexadecimal notation) is the destination MAC address on the beacon frame from 30 Munroe St??
<img width="940" height="462" alt="image" src="https://github.com/user-attachments/assets/b68e5814-9a20-4013-9233-0b7c431717f6" />
### Ans:- Destination address: Broadcast (ff:ff:ff:ff:ff:ff)


## 9 What (in hexadecimal notation) is the MAC BSS id on the beacon frame from 30 Munroe St? 

### Ans:- BSS Id: Cisco-Li_f7:1d:51 (00:16:b6:f7:1d:51)

## 10 The beacon frames from the 30 Munroe St access point advertise that the access point can support four data rates and eight additional “extended supported rates.” What are these rates?

<img width="939" height="573" alt="image" src="https://github.com/user-attachments/assets/0db4153b-2c28-43a3-aefa-776532199988" />

### Ans:- See in image


## 11  Find the 802.11 frame containing the SYN TCP segment for this first TCP session (that downloads alice.txt). What are three MAC address fields in the 802.11 frame? Which MAC address in this frame corresponds to the wireless host (give the hexadecimal representation of the MAC address for the host)? To the access point? To the first-hop router? What is the IP address of the wireless host sending this TCP segment? What is the destination IP address? Does this destination IP address correspond to the host, access point, first-hop router, or some other network-attached device? Explain.

<img width="1850" height="665" alt="image" src="https://github.com/user -attachments/assets/5862fd5e-f8fa-42be-903a-7bafd3927496" />
## Ans:- Source address: Cisco-Li_f4:eb:a8 (00:16:b6:f4:eb:a8)          Destination address: IntelCor_d1:b6:4f (00:13:02:d1:b6:4f)            BSS Id: Cisco-Li_f7:1d:51 (00:16:b6:f7:1d:51)
ransmitter Address (TA): This is the MAC address of the device sending the frame, which in this case is the wireless host.
Receiver Address (RA): This is the MAC address of the immediate recipient of the frame, which is typically the access point in an infrastructure network.
Basic Service Set Identifier (BSSID): This is the MAC address that uniquely identifies the Basic Service Set (BSS), commonly associated with the MAC address of the access point. 


## 12 Find the 802.11 frame containing the SYNACK segment for this TCP session. What are three MAC address fields in the 802.11 frame? Which MAC address in this frame corresponds to the host? To the access point? To the first-hop router? Does the sender MAC address in the frame correspond to the IP address of the device that sent the TCP segment encapsulated within this datagram? (Hint: review Figure 6.19 in the text if you are unsure of how to answer this question, or the corresponding part of the previous question. It’s particularly important that you understand this).

## Ans:- 
<img width="1850" height="665" alt="image" src="https://github.com/user-attachments/assets/65d14107-fa18-49b9-a82d-dec446ef391f" />
<img width="1850" height="665" alt="image" src="https://github.com/user-attachments/assets/25e26754-352f-4584-98e2-634b9bf68d38" />


