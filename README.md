# NMOS
NMOS characteristics (gm, rout, gmb) || CADENCE GPDK 180nm

circuit diagram and outputs attached
W= 2um, L=180nm and set VDS=0.9V, VGS=0.9V, VBS=0V

PLOT 1: ID VGS PLOT (gm value) 
DC ANALYSIS:
1. plot ID- VGS
2. sweep dc value of VGS from 0V to 1.8V
3. find derivative of ID- VGS curve to get gm curve
4. find value of gm curve at 0.9V as VGS=0.9V
RESULT OBTAINED: gm= 906.95 uS

PLOT 2: ID VDS PLOT (rout value) 
DC ANALYSIS:
1. plot ID- VDS
2. sweep dc value of VDS from 0V to 1.8V
3. find derivative of ID- VDS curve
4. take reciprocal of deriv(ID-VDS) to get rout curve
5. find value of rout curve at 0.9V as VDS=0.9V
RESULT OBTAINED: rout= 25.7815 kΩ

PLOT 3: ID VBS PLOT (gmb value) 
DC ANALYSIS:
1. plot ID- VBS
2. sweep dc value of VBS from -1V to +1V
3. find derivative of ID- VBS curve
4. find value of gmb curve at 0V as VBS=0V
RESULT OBTAINED: gmb= 271.5 uS

