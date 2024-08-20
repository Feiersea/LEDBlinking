HDL programs consists of three portions; The I/O ports, The signal Declaration, and the body portion.
Reminder that the code is not executed sequentially, but rather all at once.
// for single line comments and --similar to Java--
/* comment
   comment * / for multiline comments.
The format for Number Representation is [sign][size]'[base][value] 
*/ Example: 5'b11010 //This would be a 5 bit binary number (b indicating binary)* 
the format for I/O declaration is 
module [module name]
  {
  [node] [data_type] [port_names],
  [node] [data_type] [port_names],
  };
Example: 
module eq1
  (
  input wire i0, i1,
  output wire eq
  ); 
Program Body
Outline: assign [signal_name] = [expression].
Example: assign eq = p0 | p1;
Remember that | is an or operator.
When p1 or p0 change their value the value of eq will then change after the propogation delay
Signal Declaration
Outline: [data_type] [port_names];
Example: wire p0, p1;
vlsi point videos
