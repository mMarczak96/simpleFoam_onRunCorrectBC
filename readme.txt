A solver developed to test dynamic changes of BC value implemented into the source code and the BC.
Proved functionality. Can be used as a tempalte for later development.

How it works:
Pressure-velocity coupiling is nested into loop that every iteration increases the inlet velocity by (0.1 0 0 ) m/s.
A value of the new inlet velocity is calculated in the source code, but the use of it is achieved in the inlet BC in 0 directory.

It has been checked that no <U.correctBoundaryConditions()> function is needed to change values on the inlet patch.
