
 
 # refGenes - Reference Genes Analysis
   This pipeline performs an automated analysis of the three most used algorithms to verify the stability of reference genes
 
## STEP.1 -Download this repository to a preference path:<br>
	# Cloning the whole repository (Git is required)
	# Open the terminal on unixOS and navigate to your work directory
   	 $ git clone https://github.com/hanielcedraz/refGenes.git
   	 $ cd refGenes
	
	# Downloading zip file
	   - Under the repository name, click Clone or download.
	   - Click on Download ZIP
	  
## STEP.2 - Install R<br>
	Access https://cran.r-project.org


  ## Required files:
    dataset file (default: endogenous_ct.txt)
    efficiency list (default: efficiencies_list.txt)

  ## Usage on linux or Mac OS terminal: </br>
    $ ./refGenes.R -f dataset_file.txt -e efficiency_list.txt
    
    
    
    Obs. Also you can open the refGenes.R file with your favorite R IDE and follow the script (not recomended)
    
    
|   GeneName    |   SD_Value    |
|   ---------   |   ---------   |
|   RPL5    |   0.666    |
|   MRPS27  |   0.819    |
|   HPRT1   |   0.832    |
|   HMBS    |   0.836    |
|   MRPS30  |   0.92     |
|   EEF1    |   0.926    |


![Gene Stability measured by NormFinder](https://ibb.co/Fnk2QBB)
