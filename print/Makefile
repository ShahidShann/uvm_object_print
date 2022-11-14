all:
	rm -rf uvm_object_print.log
	rm -rf work 
	clear
	vlib work;
	vlog uvm_object_print_tb.sv && vsim uvm_object_print_tb -l uvm_object_print.log -c -do "run -all;quit;"

compile:
	vlib work;
	vlog uvm_object_print_tb.sv

simulate:
	vsim uvm_object_print_tb -l uvm_object_print.log -c -do "run -all;quit;"

clear:
	rm -rf uvm_object_print.log
	rm -rf work
	clear
