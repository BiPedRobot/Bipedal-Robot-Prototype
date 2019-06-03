Example_Make: TextFile0 TextFile1
	cat file0.txt >> file1.txt
TextFile1: file0.txt
	touch file1.txt
	echo "example" > file1.txt
TextFile0:
	touch file0.txt
	echo "Makefile " > file0.txt
