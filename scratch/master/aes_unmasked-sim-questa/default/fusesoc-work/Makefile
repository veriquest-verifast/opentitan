all: lowrisc_dv_aes_sim_0.1

lowrisc_dv_aes_sim_0.1: lowrisc_dv_aes_sim_0.1.scr
	$(EDALIZE_LAUNCHER) vcs -full64 -top tb -f lowrisc_dv_aes_sim_0.1.scr -o $@  -sverilog
run: lowrisc_dv_aes_sim_0.1
	./lowrisc_dv_aes_sim_0.1 -l vcs.log 
clean:
	$(RM) lowrisc_dv_aes_sim_0.1
