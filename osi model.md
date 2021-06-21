# OSI Model
> The Open Systems Interconnection model is responsible for creating a communication path over a network between two systems. It uses seven layers and those seven layers have some unique responsibility to make a digital request to convert an analog and analog to digital so that communication happens. 

## List of OSI Model
<img src="images/osi.png" />

## Application Layer
> Application layer is used by network application like chrome, firefox or other web browser and those application does not reside in the application layer but they used application layer protocol to work. Application layer provides some protocol like HTTP/S, FTP, SMTP, TELENET, POP3 and etc. to perform user activities.

<img src="images/application layer.png" />

## Presentation Layer
> Presentation layer receives data from the Application layer in the form of numbers and characters and it converts them to binary format. This conversion is called translation and also compressed data lossless or lossy manners so that data transmission can be done faster. Also before transmission data is encrypted and enhanced the security of data. SSL is used for data encryption/decryption.

<img src="images/presentation layer.png" />

## Session Layer
> Session layer create communication channels, managing connections and enabling sending and receiving data.

<img src="images/session layer.png" />

## Transport Layer
> In Transport layer data received from the session layer in a small piece of data unit is called segments. Each segment contains a source and destination port also with the sequence number. It also controls data flow and handles the error. Transport layer sends segment to the Network layer.
> > Protocols:
> > TCP and UDP

<img src="images/transport layer.png" />

## Network Layer
> Network Layer worked for the transmission of the received segments. Network layer creates IP packet from received segments and assigns sender and receiver IP to packet. Network layer work with IP address. Logical addressing is done in this layer.

<img src="images/network layer.png" />

## Data Link Layer
> Physical addressing is done at the Data link layer. Source and destination MAC address are assigned in each data packet to form a frame. This frame is a binary sequence.

<img src="images/data link layer.png" />

## Physical Layer
> Physical layer converts binary sequence to signals.

<img src="images/physical layer.png" />