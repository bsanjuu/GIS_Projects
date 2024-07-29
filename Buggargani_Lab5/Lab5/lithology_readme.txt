The *.lth file is a database file that can be added as a table within your project, and linked to the
attribute table of the corresponding water wells theme via the WELLID common field.  This creates a 
one-to-many link relationtionship with the *.lth table as the source table, and the theme attribute table 
as the destination table.

All information is exactly as was entered on the well log by the water well drilling contractor.  The 
following is a definition of the Lithology fields:

SEQNO (Sequence number)- Sequential numbering of all the strata associated with a well, ordered from 
surface to bottom of well.

PRIMLITH (Primary lithology)- Primary material of the stratum.

LITHMOD (Lithology modifier)- Where applicable, a modifying descriptor of the primary lithology.

DEPTH- Measurement from surface to bottom of the stratum, in feet.

THICKNESS- Measurement from top of stratum to bottom of stratum, in feet. 

AQTYPE (Aquifer type)- Characterization of the primary lithology into one of 3 types:  
D = drift
R = rock
U = unknown  

CLASS- Further characterization of the primary lithology into one of 4 classes:
AQ  = aquifer material
MAQ = marginal aquifer material
CM  = confining material
PCM = partially confining material

EFFECT- Numerical representation of the LITHMOD field.  This is an intermediate value used in deriving the final field 
MAQTYPE, it is not applicable as a separate attribute.

MAQTYPE (Modified aquifer type)- The final characterization of the strata.  Derived by expression by 
combining the PRIMLITH & LITHMOD fields, there are 4 choices for this field:
AQ  = aquifer material
MAQ = marginal aquifer material
CM  = confining material
PCM = partially confining material



For questions, contact:

Andy LeBaron, Michigan Department of Environmental Quality
phone: (517) 241-1435
email: lebarona@michigan.gov

Ronda Page, Michigan Department of Environmental Quality
phone: (517) 241-1380
email: pagerc@michigan.gov