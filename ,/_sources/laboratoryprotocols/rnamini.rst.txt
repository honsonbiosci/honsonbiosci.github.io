RNA Miniprep
============

This protocol is intended to replace Qiagen's RNEasy Miniprep Kit. It has been tested in NIH3T3 cells and gives comparable yield and quality to the commercial kit. To steer clear of possible legal issues (and make the protocol more comprehensible) the names of buffers have been changed. The buffer formulations here are my best guess at Qiagen's formulas, but they may not be identical and therefore may perform differently in some cases. 

Materials
-----------------------

In-House Reagents
^^^^^^^^^^^^^^^^^

`Buffer calculator <https://docs.google.com/spreadsheets/d/1EITWwn0JGvGQS48zH_d1t2Xg49ATznKb/edit?usp=sharing&ouid=110781881215035430006&rtpof=true&sd=true>`_

GuSCN Lysis Buffer

   4M guanidinium thiocyanate (GuSCN)

   55mM Tris-HCl, pH 7.5

   25mM EDTA

   3% Triton X-100

Wash Buffer 1

   20% ethanol

   900mM GuSCN

   10mM Tris-HCl, pH 7.5

Wash Buffer 2

   80% ethanol

   100mM NaCl

   10mM Tris-HCl, pH 7.5

70% ethanol

Plastics and Beads
^^^^^^^^^^^^^^^^^^

Zymo IIC Columns

Zymo Collection Tubes

For DNase Treatment
^^^^^^^^^^^^^^^^^^^

ThermoFisher Turbo DNase and 10x Turbo DNase Buffer

RNase Inhibitor (Ribolock or similar)

RNA Miniprep Protocol
---------------------
1. Collect cells as appropriate for sample, then resuspend pellet in GuSCN Lysis buffer. Incubate cells 3-5 min at room temperature to allow RNA-protein complexes to disassemble.

  .. list-table::
     :widths: 25 25 
     :header-rows: 1
   
     * - Number of cells
       - Volume GuSCN Lysis Buffer (µl)
     * - <5M
       - 350
     * - 5-10M
       - 600

2. Add one volume 70% ethanol to lysate.

3. Transfer 700µl sample to Zymo IIC column. Spin 15s, >12,000g. Discard flow-through and repeat for any remaining sample.

4. Add 700µl Wash Buffer 1 to the column and spin 15s, >12,000g. Discard flow-through.

5. Add 500µl Wash Buffer 2 to the column and spin 15s, >12,000g. Discard flow-through.

6. Add 500µl Wash Buffer 2 to the column and spin 1min, >12,000g. It is essential to spin for at least 1min to completely dry the column. Discard the flow-through.

7. If any liquid remains on the column, transfer to a clean collection tube and spin again 1min, >12,000g to completely dry the column. (Normally, this step is unnecessary). 

8. Transfer column to a clean 1.7mL tube. If not proceeding immediately with DNase treatment, elute DNA/RNA by adding 30µl nuclease-free water or TE buffer directly to the column. If proceeding immediately to DNase, add 24.5µl nuclease-free water or TE buffer. Yields may be improved by allowing the elution buffer to remain on the column for 3-5min before spinning, but this is generally unnecessary.

9. Spin 1min, 12,000-16,000g. I do not recommend spinning higher than 16,000g as this tends to break the lids of the tubes.

10. Discard the column. Proceed immediately to DNase treatment or store eluted DNA/RNA mixture at -80°C.

DNase Protocol
--------------

1. Add 3µl 10x Turbo DNase buffer, 2µl Turbo DNase, and 0.5µl Ribolock RNase Inhibitor to 24.5µl RNA.

2. Incubate 20min, 37°C.

3. Clean RNA using Zymo RNA Clean and Concentrate or similar kit. DNase can also be inactivated by adding 15mM EDTA and heating 10min, 75°C but this may affect RNA quantification and metal cation dependent downstream applications. 

Protocol Notes
--------------
* GuSCN dissolution is endothermic. I recommend heating GuSCN solutions to 37°C to facilitate dissolution.

* Prepare all solutions with nuclease-free water.

* The Guttman lab uses Turbo DNase extensively and we have not observed RNase activity. Other DNases should be tested for RNase activity before using in RNA protocols.

Hazards and Waste Disposal
--------------------------
* Consult the Safety Data Sheet for any unfamiliar reagents and comply with local regulations regarding disposal of hazardous waste.

* GuSCN is a powerful chaotrope. Always wear gloves and a labcoat when handling GuSCN. Do not open solid GuSCN outside of a fume hood and dispose of all liquid and solid waste in dedicated containers.

* GuSCN solutions release hydrogen cyanide gas when exposed to acids or oxidizers such as bleach. Always use caution when preparing or disposing of GuSCN solutions.
