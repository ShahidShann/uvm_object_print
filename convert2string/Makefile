all:
	rm -rf uvm_object_con2str.log
	rm -rf work
	clear
	vlib work;
	vlog uvm_object_con2str_tb.sv && vsim uvm_object_con2str_tb -l uvm_object_con2str.log -c -do "run -all;quit;"

compile:
	vlib work;
	vlog uvm_object_con2str_tb.sv

simulate:
	vsim uvm_object_con2str_tb -l uvm_object_con2str.log -c -do "run -all;quit;"

clear:
	rm -rf uvm_object_con2str.log
	rm -rf work
	clear
