# NeTV2 FPGA EDID Snooper

This block snoops transactions on the EDID bus and
records the data to memory. Access the results using
the Vivado AXI GPIO expander with a cheesy bit-bang
regsiter interface.

This basically allows the host to see what resolution
modes are supported by the source and sink.

It's tested to work with Vivado 2016.1.
