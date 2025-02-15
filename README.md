# Mouse_Respiration

#Project in collab with Monique Smith's lab 

# Repo contents: 

RespirationProject.ipynb - analysis code 

Dyad1Exp1:
 vOBrr* - raw data files 
 bycycle* - bycycle output files 

Dyad1Exp2: 
 Dyad1Exp2* - raw data files
 bycycle* - bycycle output files

 Dyad3Exp1: 
    Dyad3Exp1* - raw data files
    bycycle* - bycycle output files

 Dyad3Exp2: 
    Dyad3Exp2* - raw data files
    bycycle* - bycycle output files

Dyad1_all_data_moving.txt - txt file containing concatenated bycycle outputs for all mice in dyad1 
    group = pain (1) vs bystander (2) mouse 
    time = pre (1) vs post (2) injection 
    experiment = exp1 (1) vs exp2 (2)
    mouse_id = bystander in exp1 is mouse 2; cap mouse in exp1 is mouse 1 
    dyad = 1

Dyad3_all_data_moving.txt - txt file containing concatenated bycycle outputs for all mice in dyad3 
    group = pain (1) vs bystander (2) mouse 
    time = pre (1) vs post (2) injection 
    experiment = exp1 (1) vs exp2 (2)
    mouse_id = bystander in exp1 is mouse 4; cap mouse in exp1 is mouse 3 
    dyad = 3

All_data_moving.txt - txt file containing bycycle outputs from mice in dyad1 & dyad3
	group = pain (1) vs bystander (2) mouse 
	time = pre (1) vs post (2) injection 
	experiment = exp1 (1) vs exp2 (2) 
    dyad = 1 or 3 

Movement Data (Sorted by dyad/exp/mouse/time - ex: D1E1_ByPre is dyad1, experiment1, bystander, pre - files without the 'By' tag recieve capsaicin)
    Key to movement - moving (1) vs non-moving (0)
    Key to movement_type - non-moving (0), walking (1), rearing (2), grooming (3), sniffing (4), allosniffing (5), licking (6), allogrooming (7), allolicking (8)