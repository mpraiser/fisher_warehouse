branch
|               |branch2 
|  s2           | m5
|  m2           | s5
|               |
|               |
|               |      
|  main   m3    |              main2 m6       [  ]
|-------------- |  [  ]  -------------------  [  ] storage              [   ] storage output device
|         s3        cube              s6      [  ]    m7 s7                        m8
|                   m4
|
|
|   s1
|   m1
|
input


IF1:
	M1 input
	M2 input_branch, input_main, input_main2
	M3 input branch2
	M4 cube

	I1 input
	I2 input_branch
	I3 input_main
	I4 input branch2
	I5 input_main2
	I6 storage
	I7
	I8

EM1:
	M1 storage_out
	M2 storage