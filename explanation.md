### What's going on in `Mystery.sol`?

##### Answer:
It calls the default function on the contract at the address passed into the constructor. We get the call data (i.e. the method signature and parameters), perform the call, and return the output data. If the call fails, we jump to a bad location.

Drew Kaul 3032680315
Felipe Campos 3032752530
