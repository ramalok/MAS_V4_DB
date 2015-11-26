## Sanger environmental marine sequences of the V4-V5 regions

    Database name: MAS_V4_DB
    Version : 8952 | 15 November 2015
    	Older versions: 8903 | 11 November 2015 
    Contact: ramonm at icm.csic.es

### DESCRIPTION

    Sanger environmental marine sequences of the V4-V5 regions, retrieved until January 2010. 
   
    Classified to class-level using phylogenetic trees
    
    Further modifications to add missing taxa

    8952 sequences, about 500 bp in size


### SOURCE 

    Based on the sequences presented in Pernice et al. 2013. PLoS ONE 8:e57170 		(http://dx.plos.org/10.1371/journal.pone.0057170)


### HISTORY OF THE DATASET

	- Initially there were 8291 Sanger sequences classified in 65 taxonomic groups
	
	- These were grouped at 99% with Usearch (~3304 sequences) and then were further verified with a few extra changes
	
	- Metazoans and fungi were downloaded from PR2, and also grouped at 99% with Usearch. This resulted in 3593 additional sequences
	
  	- Add stramenopiles (including MAST and MOCH clades and subclades) as in Massana et al. 2014. ISME J. 8: 854-866
  	
  	- Adds opisthokonta including del Campo & Ruiz-Trillo 2013. Mol. Biol. Evol. 30:802–805


### ADDITIONAL COMMENTS	- LIMITATIONS

    - Amoebozoa not separated in classes

    - Chlorophyta lacks all classes except Prasinophyceae (including Mamiellophyceae)  and Trebouxiophyceae

    - Metazoa not separated in classes
    
    - On the other hand, excavata highly separated
    
    - Fungi checked individually
	      Ascomycota - Perfect
	      Basidiomicota - Perfect
	      Mucoromycota - Perfect
	      Chytridiomycota - Rather good
	      Cryptomycota - Perfect

	  There is a clade that includes all Blastocladiomycota, together with smaller clades
	  with a fraction of Entomophthoromycota, Kickxellomycota, Zoopagomycota, Chytridiomycota, 
	  and Mucoromycota
	

### Changes in version 8952 (15-11-2015)

	Based on MAS_V4_8903 with the following modifications

	1 - Add missing taxa within previous groups (6): 3 Dinophyceae; 1 Layrinthulomycete; 2 MALV-I
	
	2 - Add missing groups (22)
		Ellobiopsidae (3)
		Nephroselmis (3)
		Ulvophyceae (2)
		Chlorophyceae (1)
		Rhodophyta (13)
	
	3 - Add nucleomorphs
		Retrieve all OTUs classified as nucleomorphs (98 OTUs)
		Cluster them at 97% similarity - 21 OTUs remaining
		Do a GenBank search for similar sequences
		Add 21 nucleomorphs
	
	4 - Align all these 49 sequences together with some references from Massimo and cut to 
		keep the V4-V5 regions
	
	5 - Separate Mamiellophytes (and Chlororendrophyceae) from Prasinophyceae

	Present limitation (to imporve in the future)
		Separate Amoebozoa in classes

	



