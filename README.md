Another reference script for generating random DNA sequence. 

Simply execute the script followed by length of the DNA you want to synthesize.   

./dna_synth.sh 30000 will return a fasta formatted file (with a > header) of 3000 bases    

For reference, a netbook with Celeron N3060 processor and 4GB of ram running Ubuntu Mate 20.10 on battery generating a sequence the size of Deinococcus radiophilus genome takes below time from start to finish.   

~~~
real	0m2.681s
user	0m2.495s
sys	0m0.443s
~~~

A computer with Ryzen 9 5950x and 64GB of ram completed the same task in:  

~~~
real	0m0.455s
user	0m0.461s
sys	0m0.037s
~~~

A 100bp example fasta output is included, generated via ./dna_synth.sh 100   
CLI output for the process was :

~~~

##################################################
     Total sequence composition is as follows     
--------------------------------------------------
     22 A
     32 T
     24 C
     22 G
--------------------------------------------------
     GC content is 46.00 %                  
##################################################

~~~ 
 
