# Classification of Texts written by ESL students from European and Asian countries 

Disclaimer: This project was done as a part of the course requirement for MDS-CL program (UBC MDS-CL COLX 521). 

This project creates an end-to-end classification system using a corpus of HTML documents scrapped from the Lang-8 language learning website. In particular, we build a classifier to distinguish English text written by Lang-8 users whose native language (L1) is another European language (French and Spanish) from those written by L1 speakers of East Asian languages (Japanese, Korean, and Mandarin Chinese). 

The members of this group are: 

     Christina Park
     Daniel Cheng
     Jin Cho
     Sheena Salwan 
   
 (ordered alphabetically based on the first name).
 
 * Ensure that your working directory contains the following directories and files.  - data / lang-8.zip
      - data / asian_cities.txt
      - data / asian_culture.txt
      - data / asian_food.txt
      - data / dev.txt
      - data / european_cities.txt
      - data/ european_culture.txt
      - data/ european_food.txt 
      - data / irreg_pp.txt
      - data / test.txt
      - data / testfile.txt
      - data / train.txt

* Additionally, (optional) you may have data/lang-8/*.html files, which are the content of the lang-8.zip.
* The program is capable of reading html input files either in the zip file or as uncompressed files in the lang-8 directory. This is controlled by the optional parameter mode in the get_raw_data function. 
