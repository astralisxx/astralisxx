<picture>
  <source media="(prefers-color-scheme: dark)" srcset="media/banner-dark@2x.png">
  <img src="media/banner-light.png" alt="3-D booster render, in-cylinder CFD velocity, check-valve gap jet and finned-housing temperature field" width="100%">
</picture>

## Berkay Şimşek

Chemical engineer (BSc METU 2023, MSc 2026). I model high-pressure reciprocating
compressors with 3-D CFD (ANSYS Fluent) and 0-D thermodynamic models (MATLAB, Python), test them
against a laboratory rig, and build the software that puts those models to work.

### How the projects connect

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="media/pipeline-dark.svg">
  <img src="media/pipeline-light.svg" alt="Project pipeline: valve flow tests and valve CFD give the valve model; housing cool-down tests and housing CFD give the wall heat-transfer condition; both feed the 0-D model and the 3-D cylinder CFD, which cross-check each other and are validated on the test rig; the 0-D model, ported to Python, runs the booster simulator" width="100%">
</picture>

### Projects

**Compressor research**

<table>
<tr>
<td width="33%" valign="top">
<picture><source media="(prefers-color-scheme: dark)" srcset="media/cards/thumb-compressor-cfd-dark.png"><img src="media/cards/thumb-compressor-cfd.png" alt="Velocity field in the compressor cylinder during the stroke" width="100%"></picture>
<p><a href="https://github.com/astralisxx/reciprocating-compressor-cfd"><b>Reciprocating compressor CFD</b></a><br>
MSc thesis work: transient 3-D dynamic-mesh CFD of a high-pressure nitrogen compressor cylinder, with check-valve dynamics and wall heat transfer in C UDFs.</p>
</td>
<td width="33%" valign="top">
<picture><source media="(prefers-color-scheme: dark)" srcset="media/cards/thumb-check-valve-dark.png"><img src="media/cards/thumb-check-valve.png" alt="Velocity in the gap of a ball check valve" width="100%"></picture>
<p><a href="https://github.com/astralisxx/check-valve-cfd"><b>High-pressure check valves</b></a><br>
Steady 3-D CFD and flow experiments of the compressor's ball check valves, matched to infer lift and effective flow area.</p>
</td>
<td width="33%" valign="top">
<picture><source media="(prefers-color-scheme: dark)" srcset="media/cards/thumb-heat-transfer-dark.png"><img src="media/cards/thumb-heat-transfer.png" alt="Temperature field of a finned compressor housing" width="100%"></picture>
<p><a href="https://github.com/astralisxx/compressor-heat-transfer"><b>Compressor heat transfer</b></a><br>
Cool-down experiments and conjugate CFD of the finned housings give the wall heat-transfer condition for the 0-D and 3-D models.</p>
</td>
</tr>
</table>

**Software**

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/astralisxx/logos-yb690-booster"><img src="media/cards/thumb-booster.jpg" alt="3-D cutaway of the two-stage booster in the simulator" width="100%"></a>
<p><a href="https://github.com/astralisxx/logos-yb690-booster"><b>LOGOS-YB690 Booster</b></a><br>
Desktop simulator and inverse-design tool for a two-stage reciprocating gas booster. Real-gas physics core in Python/SciPy, tested against the MATLAB reference models; FastAPI, Tauri, three.js.</p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/astralisxx/the-factory-showcase"><img src="media/cards/thumb-factory.png" alt="A room on The Factory's isometric ship" width="100%"></a>
<p><a href="https://github.com/astralisxx/the-factory-showcase"><b>The Factory</b></a><br>
Desktop app that runs command-line coding agents as a robot crew on an isometric ship: missions as pipelines, approval gates, Keep/Undo, and a benchmark harness.</p>
</td>
</tr>
</table>

**Other CFD**

<table>
<tr>
<td width="33%" valign="top">
<picture><source media="(prefers-color-scheme: dark)" srcset="media/cards/thumb-woven-screen-dark.png"><img src="media/cards/thumb-woven-screen.png" alt="Velocity jet through the opening of a woven wire screen" width="100%"></picture>
<p><a href="https://github.com/astralisxx/woven-screen-cfd"><b>Woven wire screen</b></a><br>
Resolved 3-D CFD in OpenFOAM of flow and a fast surface reaction on a fine woven screen, checked against pressure-drop and mass-transfer correlations.</p>
</td>
</tr>
</table>

The source code of these projects is private.

### Research

- **Conference paper.** A. B. Şimşek, B. Erdoğan, N. B. Üner, "Computational Design of a High-Pressure
  Compressor and Its Experimental Validation", ICCHMT 2025, Lecture Notes in Mechanical Engineering,
  Springer, pp. 390-399, 2026. https://doi.org/10.1007/978-3-032-16138-3_36
- **Conference paper.** F. Turgut, A. B. Şimşek, N. B. Üner, B. Erdoğan, "Analysis of a High-Pressure
  Reciprocating Compressor Piston's 2D Simulation Utilizing Computational Fluid Dynamics", ICBASET 2024,
  The Eurasia Proceedings of Science, Technology, Engineering and Mathematics, vol. 28, pp. 352-359, 2024.
  https://doi.org/10.55549/epstem.1523562
- **MSc thesis.** "Experimental and Numerical Design of a High-Pressure Reciprocating Compressor",
  METU Chemical Engineering, 2026. Supervisor Asst. Prof. Dr. Necip Berker Üner; co-supervisor
  Dr. Barış Erdoğan (Logos Kimya).
- **Journal manuscript** on the compressor model and its validation: in preparation.

### Tools

**CFD:** ANSYS Fluent and Meshing (dynamic mesh, UDFs in C, k-omega SST, real-gas equations of state)<br>
**Modelling:** MATLAB (stiff ODE systems), Python (NumPy, SciPy, Cantera)<br>
**Software:** FastAPI, Tauri, JavaScript, three.js, Plotly, pytest, Playwright, GitHub Actions<br>
**Experiments:** high-pressure compressor test rig, in-cylinder pressure and mass-flow measurement

### Contact

[Google Scholar](https://scholar.google.com/citations?user=OxW7kAoAAAAJ) · Ankara, Türkiye
