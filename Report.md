# Report

### GitHub repo
https://github.com/YU-LIN-LIN/ESL_HW2

### General description or introduction of the problem and your solution
	Fulfill Gaussian blur with TLM-2.0 interconnect.
### Implementation details
	Testbench is seen as initiator socket with bus as its target socket.
	Bus is an another initiator socket whose target socket is pointed to gaussian filter at the same time.
### Additional features of your design and models

	Set the appropriate address in memory to save the data that need to be filtered as bus.

### Experimental results
	Total cycles : 2686976 cycles

### Discussions and conclusions

	Use blocking transport, completing one transmission after initiator sends request and receives response.
	Through blocking transport, we can also simulate the system delay time.