### Procedure
1. Click the “Concept” tab to read the basic theory of the microstrip-slotline crossing and how magnetic coupling produces a notch response.
2. Click the “Formulas” tab to note down the resonant frequency, parallel RLC, and notch depth formulas (Knorr transformer model).
3. Click the “Design & Simulation” tab to open the design and simulation dashboard.
4. Enter the microstrip feed parameters (microstrip width Wm, substrate height h, permittivity εr, loss tangent tanδ) in the Design Parameters panel.
5. Enter the slot parameters (slot width Ws, slot length Ls) and the transformer ratio n in the same panel.
6. Observe the live-calculated values — f0 (notch frequency), Z0 of slot and microstrip, Qu, QL, Rp, notch depth, Lp, Cp — updating as you type.
7. Observe the top-view geometry (ground plane with slot, microstrip crossing on the other face) updating live, including the model-validity warning if parameters fall outside range (εr 9.7–20, Ws/h 0.02–1.0).
8. Enter the simulation frequency range (f_start, f_stop) and number of points in the Simulation bar.
9. Click the “S-Parameters” button to run the simulation.
10. Observe the |S21| (notch) and |S11| graph in dB, and the |S21| linear-scale graph.
11. Observe the standing wave pattern |V(z)| along the slot (maximum at the center, shorted ends).
12. Note the equivalent circuit description (parallel RLC slot model coupled through a 1:n transformer) and its computed values.
13. Click the “Field Distribution” button and move the frequency slider to observe field behavior at different frequencies.
14. Change one design parameter (e.g., Ls, Ws, or εr) at a time and re-run the simulation to observe its effect on notch frequency and notch depth.
15. Record all observations and write a conclusion based on the results obtained.
