This Bash script was designed to
run a bunch of different programs 
that were located inside a main
directory with different sub-directories
up to 2 down-levels, the core of the 
script represents:



    cd k=i

    cd Lj
    cd KiLj
    simple main
    cd ..
    cd ..

    cd ..



Were i is the number of the kth directory,
j of the lth sub directory and simple is 
a costum alias-alocated
script used for compiling and running 
C/C++ programs.