# IEEE8500
optimal power flow IEEE 8500 node test feeder

Edits from the original OpenDSS model: (1) the reactor at the source is ignored (R and X set at very small values). (2) loads models changed to 1, constant PQ. (3) the Vminpu parameter of loads are modified from .88 to .80 p.u. to avoid the auto-conversion from constant PQ to constant impedance.

The code requires (1) MATLAB, (2) YALMIP to call the solver (3) SeDuMi as the SDP solver.
