# pacbiohifi-analyzer
a pacbiohifi analyzer for the pacbio hifi reads and gives all the information for the pacbiohifi reads from raw to the graph alignments

- complete pacbio hifi analyzer class from reading, plotting, clipping, reading bam, generating the graphs, extracting the graph sequences coded today from start to finish.

- initiate the class as 
```
new = PACBIOHIFICLIPPER.new("samplepacbiohifi.fastq")
new.makeindex
new.getLength
new.getFasta
new.graphs # adding this evening 
new.getClippattern
new.setClipper
new.chopclipper
new.plotchips
new.networkx # adding this evening.
```
- a part of this is also written in Rubex, a parallel implementation of the C++ but less to make it easier for others. 

Gaurav Sablok \
Academic Staff Member \
Bioinformatics \
Institute for Biochemistry and Biology \
University of Potsdam \
Potsdam,Germany


