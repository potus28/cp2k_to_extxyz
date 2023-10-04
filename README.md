# cp2k_to_extxyz
Consolidates AIMD trajectory data from CP2K into the ASE friendly extxyz format.
To use, type python cp2k_to_extxyz.py path/to/cp2k/trajectory/data. If in the CWD, type "cp2k_to_extxyz.py ."
This file assumes that you have a cp2k trajectory and are using the following file names:
- cell information: "cp2k-md-1.cell"
- energy information: "cp2k-md-1.ener"
- XYZ trajectory: "cp2k-md-pos-1.xyz"
- forces: "cp2k-md-frc-1.xyz"
- stress : "cp2k-md-1.stress"
- velocity: "cp2k-md-vel-1.xyz"

After consolidating the data, the trajectory file will be written in "path/to/cp2k/trajectory/data/traj.xyz"
