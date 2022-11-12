# What is OSI Model
  * The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network. It was the first standard model for network communications
  * OSI was introduced in 1983 by representatives of the major computer and telecom companies, and was adopted by ISO as an international standard in 1984.
<br/>
<br/>
**There are seven layers in OSI model**
       * Application layer
       * Presentation layer
       * Session layer
       * Transport layer
       * Network layer 
       * Datalink layer 
       * Physical layer

<hr>
<H3>1. Application Layer</H3> 
The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and present meaningful data to users. A few examples of application layer protocols are the Hypertext Transfer Protocol (HTTP), File Transfer Protocol , Post Office Protocol , Simple Mail Transfer Protocol , and Domain Name System.

<H3>2. Presentation Layer</H3>
The presentation layer resives data from application layer this data is in the format of charecters and numbers. Presentaion layer then converts this charecters and numbers into machine understandable binary formart, this change in the format is known as **Translation**. Before the data is transmited the presentation layer reduces the number of bits that are used to represent the original data this data reduction process is known as **Data Compression**.To maintain the intigriti of data before transmission data is encrypted ,the data is encrypted at senders side and data is decrypted at recivers side.
<H3>3. Session Layer</H3>
The session layer creates communication channels, called sessions, between devices. It is responsible for opening sessions, ensuring they remain open and functional while data is being transferred, and closing them when communication ends. The session layer can also set checkpoints during a data transfer if the session is interrupted, devices can resume data transfer from the last checkpoint.
<H3>4. Transport Layer</H3>
The transport layer takes data transferred in the session layer and breaks it into **segments** on the transmitting end. It is responsible for reassembling the segments on the receiving end, turning it back into data that can be used by the session layer. The transport layer carries out flow control, sending data at a rate that matches the connection speed of the receiving device, and error control, if some data was missed transport layer uses **Automatic Repeat Request** scheme to retransmit the loss.
<H3>5. Network Layer</H3>
The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end. The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses to route packets to a destination node.
<H3>6. Datalink Layer</H3>
The data link layer establishes and terminates a connection between two physically-connected nodes on a network. It breaks up packets into frames and sends them from source to destination. This layer is composed of two parts—Logical Link Control (LLC), which identifies network protocols, performs error checking and synchronizes frames, and Media Access Control (MAC) which uses MAC addresses to connect devices and define permissions to transmit and receive data.
<H3>7. Physical Layer</H3>
The Physical layer converts the data which is in binary form into a signal to transmit over local media. at the recever the signal is receved at the physical layer and the signal is converted int bits and sent to application layer, and the application layer makes the senders message appear at recivers end.
<hr>
<H3>Reference section</H3>
  <li>More about OSI layer in this video https://www.youtube.com/watch?v=vv4y_uOneC0</li> 
