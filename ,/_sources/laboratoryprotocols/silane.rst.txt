Silane Nucleic Acid Purification
================================

This protocol describes the purification of RNA, dsDNA, and ssDNA from solution using Silane beads. Silane are paramagnetic beads functionalized with silanol, a silica-based functional group. As such, they bind nucleic acids in a similar manner to silica columns. Silane bead extractions are more time-consuming than column clean-ups due to the time it takes for the beads to dry. They are, however, more scalable as multiple samples can be processed simultaneously in strip tubes using a multichannel pipette. 

Materials
-----------------------

In-House Reagents
^^^^^^^^^^^^^^^^^

`Buffer calculation <https://docs.google.com/spreadsheets/d/1Pz6gXp8H8RrBGXYalYlve9Z-NV_xky45/edit?usp=sharing&ouid=110781881215035430006&rtpof=true&sd=true>`_

GuSCN Lysis Buffer

   4M guanidinium thiocyanate (GuSCN)

   55mM Tris-HCl, pH 7.5

   25mM EDTA

   3% Triton X-100

100% ethanol

80% ethanol

Plastics and Beads
^^^^^^^^^^^^^^^^^^

ThermoFisher Dynabeads MyOne Silane

Nucleic Acid Purification Protocol
----------------------------------

1. Thoroughly vortex Silane beads until they are in a homogenous suspension. Immediately transfer 12µl bead suspension to a 1.7mL tube. (See Protocol Notes for details on Silane bead volumes).

2. Place tube on a magnetic rack and allow the solution to clear.

3. Remove the supernatant and immediately add 500µl GuSCN Lysis Buffer. Remove tube from rack, rotate 180°, then place back in rack to pull beads through the ethanol to the opposite wall. Repeat rotation 2-3 times.

4. Place tube on the magnetic rack and allow the solution to clear. Remove the supernatant, then repeat step 3 twice more for a total of 3 washes.

5. Resuspend the beads in 3x sample volume GuSCN Lysis Buffer (e.g. for a 30µl RNA sample, resuspend the beads in 90µl GuSCN Lysis Buffer).

6. Add resuspended beads directly to the sample and pipette up and down to mix.

7. Incubate 1min, room temperature.

8. Add 100% ethanol to the sample as described in the table below (e.g. for a 120µl mixture of RNA and beads, add 120µl 100% ethanol).

  .. list-table::
     :widths: 25 25 25
     :header-rows: 1
     
     * - Sample Type
       - Volumes Ethanol
       - % Ethanol Final
     * - RNA or dsDNA
       - 1x
       - 50%
     * - ssDNA or small RNA (<100nt)
       - 3x
       - 75%

9. Incubate 3min, room temperature.

10. Place tube on the magnetic rack and allow to clear. 

11. Discard supernatant and immediately add 150µl 80% ethanol if processing in strip tubes, or 250µl 80% ethanol if processing in 1.7mL tubes. Remove tube from rack, rotate 180°, then place back in rack to pull beads through the ethanol to the opposite wall. Repeat rotation 2-3 times.

12. Place tube on the magnetic rack and allow the solution to clear. Remove the supernatant, then repeat step 11 twice more for a total of 3 washes.

13. After removing final ethanol wash, briefly pop-spin the tubes. Place on the magnet and use a P20 pipette to remove any residual ethanol.

14. Dry the beads 5-10min until they look matte. 

15. Resuspend in a convenient volume of nuclease free water for subsequent applications to elute. Magnetically pellet the beads and transfer the supernatant to a clean tube.

Protocol Notes
--------------

* I use 12µl Silane beads to clean up most reactions I perform, in general between 10ng-1µg RNA or dsDNA. For inputs above 2µg, I would recommend optimizing the Silane volume.

* Anecdotally, ssDNA seems to bind better to Silane beads than to silica columns, but its recovery is still inefficient. For ssDNA <100nt in length, increasing ethanol to 5x volume, or replacing it with 3x volume isopropanol may improve yields.

Hazards and Waste Disposal
--------------------------
* Consult the Safety Data Sheet for any unfamiliar reagents and comply with local regulations regarding disposal of hazardous waste.

* GuSCN is a powerful chaotrope. Always wear gloves and a labcoat when handling GuSCN. Do not open solid GuSCN outside of a fume hood and dispose of all liquid and solid waste in dedicated containers.

* GuSCN solutions release hydrogen cyanide gas when exposed to acids or oxidizers such as bleach. Always use caution when preparing or disposing of GuSCN solutions. 
