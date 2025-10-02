R = uv run process-run.py
h:
	$(R) -h
p1:
	$(R) -cp -l 5:100,5:100
p2:
	$(R) -cp -l 4:100,1:0
p3:
	$(R) -cp -l 1:0,4:100
p4:
	$(R) -cp -l 1:0,4:100 -S SWITCH_ON_END
p5:
	$(R) -cp -l 1:0,4:100 -S SWITCH_ON_IO
p6:
	$(R) -cp -l 3:0,5:100,5:100,5:100 -S SWITCH_ON_IO -I IO_RUN_LATER
p7:
	$(R) -cp -l 3:0,5:100,5:100,5:100 -S SWITCH_ON_IO -I IO_RUN_IMMEDIATE
