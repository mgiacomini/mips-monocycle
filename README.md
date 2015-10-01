***scMIPS***
1 - It's a simple vhdl description of Patterson and Hennessy MIPS processor.

2 - Arquitecture.pdf describe the processor like was done. To understand VHDL description it is highly recommend to follow the mentioned archive.

3 - As you see it is not a complete FPGA project. It is just .vhd files. To run and simulate the processor we recommend the lecture of links above:

	Download Xilinx ISE:
		http://www.xilinx.com/products/design-tools/ise-design-suite.html
	
	Getting a license:
		If you had problems during installation to generate your free license:
		http://www.xilinx.com/support/licensing_solution_center.htm

	Getting start with ISE:
		www.xilinx.com/itp/xilinx10/books/docs/qst/qst.pdf

4 - After install Xilinx ISE you will probably find it diffult to run it. 

Concerning Ubuntu OS the following steps should be performed.

		Open a terminal and enter:
		
		cd /opt/Xilinx/14.7/ISE_DS
		sudo gedit run_ise.sh

		Paste the following code in the end of file

		#!/bin/bash
		. /opt/Xilinx/14.7/ISE_DS/settingsXX.sh
		ise

		DON'T FORGET TO Replace settingsXX to your computer arquitecture.
	
		Save and close file.

		Back in the command line, enter:

		sudo chmod +x run_ise.sh   
		As you now it makes the file executable

		Enter:
		ise 
		We hope it is going to launch the Xilinx ISE software

Concerning Windows OS
		No necessary comments. It is just a click click and click.

5 - Questions?
	Darci Luiz Tomasi Junior
	dltj007@gmail.com
