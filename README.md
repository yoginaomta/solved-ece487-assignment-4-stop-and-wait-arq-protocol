Download Link: https://assignmentchef.com/product/solved-ece487-assignment-4-stop-and-wait-arq-protocol
<br>
Note: normally the timer value of an ARQ protocol is much more than the round-trip propagation delay (which is the summation of the propagation delay from the sender to the receiver and the propagation delay from the receiver to the sender). In Q1~Q3 of this assignment, we consider some extreme cases when the timer value is less than the round-trip propagation delay. In other words, the timer value is not appropriately set. We assume that the maximal number of retransmissions for each frame is infinite. <strong>Please note that the procedure in Q1~Q3 is NOT endless</strong>.

<ol>

 <li>The timer of a system using the Stop-and-Wait ARQ protocol has a time-out of 3 ms. The round trip propagation delay is 4 ms. We ignore other delay (and therefore, the transmission time of a frame can be infinitely small). Draw a flow diagram similar to Fig. 11.11 on Slide 32 of Lecture 4 for delivery of two data frames. Assume that from the network layer, the request for the first data frame arrives at time instant 0 ms and the request for the second data frame arrives immediately after the first ACK frame for the first data frame is received at the sender. Also assume the first transmission attempt of the first data frame is corrupted. All subsequent data frame and ACK frame transmissions are successful.</li>

 <li>Repeat Question 1 when Go-back-N ARQ is used and we assume that from the network layer, the request for the first and the second data frame arrive at time instant 0 ms and 1 ms, respectively. The number of bits in a sequence number is <em>m=2</em>. We still assume that the first transmission attempt of the first data frame is corrupted, and all subsequent data frame and ACK frame transmissions are successful.</li>

 <li>Repeat Question 1 when Selective Repeat ARQ is used and we assume that from the network layer, the request for the first and the second data frame arrive at time instant 0 ms and 1 ms, respectively. The number of bits in a sequence number is <em>m=2</em>. Different from Question 1, we assume that the first transmission attempt of the <strong>second</strong> data frame is corrupted. All other transmissions are successful.</li>

</ol>








