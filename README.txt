/---
 ---2011013248.pdf
 ---sim
		/misc 修改了isa.h, isa.c yas-grammar.lex, 添加了test.ys文件。
		/pipe 修改了psim.c， pipe-full.hcl文件
		/ptest
		/seq
		/y86-code
		Makefile
		README
 ---README.txt
 执行该程序：
 1. 进入sim文件夹
			make
 2. cd misc
			yas test.yo
 3. cd ..
 4. pipe/psim -v 1 misc/test.yo -l 100000000 
    pipe/psim -v 1 misc/test.yo -l 100000000
 5. pipe/psim -v 1 misc/test.yo -l 100000000 -t
    pipe/psim -v 1 misc/test.yo -l 100000000 -t
 