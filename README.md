# Vehicle-to-vehicle Communication System

#### By Vanshika Sinha

## Key features and constraints

This project proposes a V2V communication system where vehicles can transmit data between each other in the format of messages. There will be different criticality levels of message transmission and messages will be transmitted based on the criticality and use case to the appropriate radius. 

The communication hardware should be light-weight and portable with latency less than the human reaction time. There should be minimum number of hops for messages. 

The solution can even be extended to communication between vehicle-to-pedestrians and vehicle-to-infrastructure. 

## Protocols used

* (Dedicated Short Range Communication) DSRC protocol
* (Cellular Vehicle-to-vehicle) C-V2V protocol

## Module description

The vehicles interact using a peer-to-peer framework where each vehicle signs the data sent using cryptographic techniques and the message transmission is encrypted to prevent data manipulation and sniffing. The state of the art algorithms such as AES256 or RSA are used for encryption. 