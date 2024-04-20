# Linked list traversal in verilog
The attached xpr file contain two verilog files 

## PROBLEM STATEMENT ->
   ## In File 1: 
   Traversing linked list and comparing data of each node of linked list in verilog
   ## In File 2: 
   Traversing linked list and unhashing the hashed data of each node and also finding unwanted infinite loops in linked list which can affect traversal to every node of linked list

   ## ATTACHED PDF FILE CONTAINS PROBLEM STATEMENT.

 ## Let's breakdown the code

 ### Module Declaration:
 This declares a module named ps1 with inputs start_pt (a 5-bit vector), reset, and outputs Time_out (an 8-bit vector) and addr_out (a 5-bit vector).

 ### Parameter Definitions:
 These define various states of the FSM.

 ### Internal Registers:
 These declare internal registers to store state information, time, addresses, and other control signals.

 ### State Transition Logic:
 This block updates the state of the FSM on the positive edge of the clock based on the reset input.

 ### State Transition Behavior:
 This block defines the behavior of each state in the FSM, including transitions to the next state.

 ### Combinational Logic:
 This block contains combinational logic to perform tasks assigned to each state.

 ### Output Assignment:
 These assign outputs based on internal register values.



 
