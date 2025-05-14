
#############################################################################################################
##### 						FILES							#####
#############################################################################################################

model_1.txt
Final model

model_2.txt
Final model running only on observations with at least one pill taken
Same as model_1.txt, duplicated for convenience

model_3.txt
Final model with informative priors for the effect of sildenafil

model_4.txt
Final model with interaction between treatment and primary or secondary RP


PROFIL_DATA.txt
The data in plain text format with variables names as header
2306 observations on 50 variables
The decimal separator is the dot "."
The columns separator is the tabulation "\t"



#############################################################################################################
##### 	                                  LIST OF VARIABLES						#####
############################################################################################################# 


id_total         = unique id of the patient in the study. From 1 to 38
cycle_total	 = unique id of the block in the study. From 1 to 110
semaine_total	 = unique id of the week in the study. From 1 to 330
jour_total	 = unique id of the day in the study. From 1 to 2306

semaine_patient	 = number of the week for a given patient (NOT calendar week). There are 3 weeks in every block. From 1 to 15
jour_semaine	 = day of the week for a given week of a given block of a given patient (NOT calendar day). In chronological order. From 1 to 7
semaine_52	 = calendar number of the week. From 1 to 52

hiver	         = number of the winter. 1=2013-2014 , 2=2014-2015
hiver1	         = 1 if hiver==1, else 0
hiver2	         = 1 if hiver==2, else 0

cycle_patient	 = number of the block for a given patient. From 1 to 5
cycle1	         = 1 if cycle_patient==1, else 0
cycle2	         = 1 if cycle_patient==2, else 0
cycle3	         = 1 if cycle_patient==3, else 0
cycle4	         = 1 if cycle_patient==4, else 0
cycle5	         = 1 if cycle_patient==5, else 0

cycle_patient_hiver = number of the block for a given patient in a given winter. From 1 to 4
cycle_ph1	    = 1 if cycle_patient_hiver==1, else 0
cycle_ph2	    = 1 if cycle_patient_hiver==2, else 0
cycle_ph3	    = 1 if cycle_patient_hiver==3, else 0
cycle_ph4	    = 1 if cycle_patient_hiver==3, else 0

ordre	         = order of treatments in a given block of a given patient. From 1 to 3
ordre1	         = 1 if ordre==1, else 0
ordre2	         = 1 if ordre==2, else 0
ordre3	         = 1 if ordre==3, else 0

ttt	         = treatment arm. 1=placebo, 2=low dose, 3=high dose
ttt1	         = 1 if ttt==1, else 0
ttt2	         = 1 if ttt==2, else 0
ttt3	         = 1 if ttt==3, else 0

rcs	         = RCS score (outcome 1). From 0 to 10

nb_crises	 = daily number of attack (outcome 2). From 0 to 9
jourdecrise	 = 1 if nb_crises>0, else 0

duree_tot	 = cumulative daily duration of attacks in minutes (outcome 3). From 0 to 755 minutes

nb_prises	 = number of pills taken by the patient. From 0 to 2
prise0	         = 1 if nb_prises==0, else 0
prise1	         = 1 if nb_prises==1, else 0
prise2	         = 1 if nb_prises==2, else 0

age	         = age in years. From 18 to 74
homme	         = male gender. 1=yes, 0=no
second	         = secondary RP. 1=yes, 0=no
inhib	         = calcium inhibitor. 1=yes, 0=no
temp	         = outdoor temperature in Celsius. From -4 to 18.4
humid		 = outdoor humidity percentage. From 40 to 99

mean_age	 = mean of age in years
agecentre	 = age - mean_age
mean_temp	 = mean of outdoor temperature
tempcentre	 = temp - mean_temp
mean_humid	 = mean of outdoor humidity
humidcentre      = humid - mean_humid
