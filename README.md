# DDS-RFSoC

### DDS implemented on the Zynq RFSoC with sampling clock of 6.8 GHz <br>
The DDS implementation requires one input - a 32 bit integer - to be sent into the FPGA, and generates the corresponding sine wave from port A of the board. The input $N_{actual}$ is related to the desired output frequency $f_{out}$ by the following relation: <br>
$f_{out} = f_{clk} \dfrac{N_{actual}}{2^{32}}$, <br>
where $f_{clk} = 6.88128 \rm{GHz}$. <br><br>
The included Jupyter notebook can be used to program the FPGA.
