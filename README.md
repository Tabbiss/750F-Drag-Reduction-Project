# Overall Drag Reduction of a 750F Race Car
<img width="374" height="334" alt="image" src="https://github.com/user-attachments/assets/0bf2c6e0-dd8a-4ee8-93e9-37199c58f846" />

## Overview

This project aimed to reduce overall drag of a 750F car by 10%. Simulations were performed using Siemens Star-CCM+.

## Objectives

* Complete full baseline analysis of 750F car including both quantative and qualitative data.
* Modify the exsisting model to reduce drag by 10% while maintaining lift characteristics. Creating 3-5 design iterations.
* Produce a final low-drag aero package that complies with 750F regulations.

## Methodology

* 3D CAD model of 750F car was imported into Star-CCM and extensively repaired.
* An open road test area was created with a moving floor section.
* A mesh convergence study was carried out to detemrine the most efficient mesh refinement.
* Steady-state simulations were run at a calculated average race speed of 39m/s.
* New field functions created to display pressure coefficient in the X and Z directions.
* Versions 1-5 created through Star-CCM surface repair tools and Catia V5 for creating new parts.

## Planned Versions
Version 1 - Cut-outs to the rear of the vehicle to reduce drag caused by the rear wheel arches.

Version 2 - Re-profiled roll hoop to reduce wake.

Version 3 - Extended and tapered rear bodywork to minimise the rear wake of the car.

Version 4 - Wind deflector on the front cockpit to protect the driver from high-velocity airflow.

Version 5 - Add slots to the end plates to reduce wake and positive lift on rear bodywork. Extend and lower diffuser end fences to maximise regulations, reprofile diffuser surface to create a smooth transition from floor to diffuser.

## Results

* Identified main drag areas on the car.
* Changes were made to reduce drag in the cockpit and rear body areas, totalling a 10% reduction.
* The final car did expereince a loss in negative lift when compared to the baseline, particularly due to the modification seen in Version 3.
* The diffuser was modified to improve efficiency and reduce tyre wake ingestion, improving negative lift characteristics with no drag penalty.

## Model Preperation
Initial geometry import - Showing the errors present including pierced face, free edges and non-manifold edges. This was fixed by importing each part seperately and using the boolean unite tool to unite them back together.
<img width="451" height="248" alt="image" src="https://github.com/user-attachments/assets/8cf6030a-2d88-4839-870f-7da0eca5bc0c" />

Rear Cockpit - The CAD model that was provided for this project does not feature any internal flows, this issue is mostly relevant to the rear cockpit structure as on the real car it acts as an intake for the engine bay area. Without the internal flow, the intake for the rear cockpit must be filled to create a closed surface which in turn, create a bluff body which will cause inaccuracies in drag values for the car.
To fix this, the 3D-CAD Editor in Star-CCM was used to add a radius to the leading edge of the cockpit, allowing for airflow to more easily remain attached as it flows over the top of the rear cockpit.
<img width="229" height="146" alt="image" src="https://github.com/user-attachments/assets/9218d262-d2ce-40fa-92b5-146c2c046c67" />

Roll Hoop - The provided roll hoop was not an accurate representation of the roll hoop on the real car. To rectify this, the roll hoop was completely remade in Catia V5 to produce a part which is representative of the actual car.
<img width="214" height="187" alt="image" src="https://github.com/user-attachments/assets/6873fab1-d2ef-404b-86ea-98b01fbf26e3" />

## Baseline 750F Car
Baseline 750F race car

<img width="846" height="407" alt="image" src="https://github.com/user-attachments/assets/b955c174-c118-4310-aea2-d97455541834" />
</div>
</p>
<hr>
Baseline Quantitative Data

<img width="210" height="144" alt="image" src="https://github.com/user-attachments/assets/41e01e74-0626-49e4-a2fa-465fb8193fb9" />

Front and rear CPx distribution - Areas in red highlight the main drag areas.

<img width="915" height="354" alt="image" src="https://github.com/user-attachments/assets/26ff2bbd-5fed-462f-a05d-56a4b1a3fd3b" />

Isosurface - Highlights the wake caused by the roll hoop, rear body, and the effect it has on the diffuser.

<img width="420" height="259" alt="image" src="https://github.com/user-attachments/assets/87e25543-1946-4357-833d-19bfa796a003" />

## Version 1
Version 1 Modification - Rear end cut outs to reduce pressure drag in the wheel arch and allow airflow to pass into the low pressure region behind the car.

<img width="358" height="170" alt="image" src="https://github.com/user-attachments/assets/93d33e93-b788-43c8-ba5e-988f56444dbf" />

Version 1 Quantitative Data

<img width="417" height="122" alt="image" src="https://github.com/user-attachments/assets/e06a9bb9-2084-4ce0-a466-24464191df2f" />

CPx Comparison - An increase in drag on the rear wheels along with a change in CPx distribution on the rear end mean that the drag savings are minimal.

<img width="435" height="256" alt="image" src="https://github.com/user-attachments/assets/a2113368-cfa5-458a-9c4a-f50d0ba2e027" /> 
<img width="240" height="268" alt="image" src="https://github.com/user-attachments/assets/88b2a5d1-61da-4aad-83a0-c94ac8ed22d6" />

Pressure Plane Comparison - Highlights the face that only a small amount of airflow passes through the cut-out, showing that they are oversized.

<img width="623" height="292" alt="image" src="https://github.com/user-attachments/assets/3cdf825d-93ee-406c-9783-92efe0f215d0" />

CPz - The cut-outs generate more negative lift at the rear of the vehicle due to the airflow accelerating into the cut-out.

<img width="346" height="269" alt="image" src="https://github.com/user-attachments/assets/8f3bfc33-ca92-4a90-b001-d1ad9908717d" />

## Version 2
Version 2 Reprofiled Roll Hoop - New hoop profile and final part.

<img width="257" height="205" alt="image" src="https://github.com/user-attachments/assets/89961ad1-f689-46f1-8bcd-096311ad606e" /> <img width="239" height="193" alt="image" src="https://github.com/user-attachments/assets/f5be016b-1cd2-4156-8db6-884027fc962b" />

Version 2 Quantitative Data

<img width="426" height="121" alt="image" src="https://github.com/user-attachments/assets/51dd6900-51c7-4d5c-a625-dd6b5737c87e" />

Roll Hoop CPx Comparison - New hoop profile reduces the wake caused by the roll hoop.

<img width="602" height="245" alt="image" src="https://github.com/user-attachments/assets/650489d5-083e-48eb-bd3d-09ba55bb699b" />

Streamline Comparison - New hoop profile better protects the rear wing from interference from the roll hoop wake, increasing negative lift.

<img width="765" height="178" alt="image" src="https://github.com/user-attachments/assets/e2fde354-f9be-4b4c-8b6e-2338c7648f42" />

## Version 3
Version 3 Extended Rear Bodywork - Bodywork extended and tapered in to reduce the rear wake.

<img width="373" height="256" alt="image" src="https://github.com/user-attachments/assets/6d280f4b-06f6-41b7-a3ef-93d004ce077a" />

Version 3 Qualitative Data

<img width="374" height="121" alt="image" src="https://github.com/user-attachments/assets/130c44df-fe0a-4b9b-aa20-2ee7478d8f11" />

Rear Bodywork CPz Comparison - Highlighting the main negative lift losses due to airflow acceleration over the downwashing rear end.

<img width="428" height="267" alt="image" src="https://github.com/user-attachments/assets/b85d41f5-cea3-4648-bd90-ce88a22ef6cf" />

Velocity Plane Comparison - Shows the extended rear bodywork minimising the wake at the rear of the vehicle, reducing drag.

<img width="783" height="188" alt="image" src="https://github.com/user-attachments/assets/ee30e46f-b72b-41f4-97a8-f018b4330c59" />

## Version 4
Version 4 Wind Deflector - Mounted to the front bodywork to deflect airflow away from the driver.

<img width="355" height="167" alt="image" src="https://github.com/user-attachments/assets/fe13d4af-0162-471c-b3c5-1bdb3a21a283" />
<img width="485" height="248" alt="image" src="https://github.com/user-attachments/assets/0bd62139-74d2-4b6e-b148-60d2c23e0363" />

Version 4 Quantitative Data

<img width="364" height="119" alt="image" src="https://github.com/user-attachments/assets/5cf5b0da-b8e3-471f-8f1c-148c2a353a32" />

Version 4 CPx Comparison - The main drag reduction can be seen around the lower portion of the driver's helmet and chest areas.

<img width="415" height="253" alt="image" src="https://github.com/user-attachments/assets/d20d4ec5-5415-4f9f-8ea3-e839db5dfc11" />

Version 4 Velocity Plane Comparison - Highlights the effect of the deflector in lifting the incoming high-velocity airflow and protecting the driver.

<img width="414" height="392" alt="image" src="https://github.com/user-attachments/assets/a49febfa-23be-4719-9a94-60d150006841" />

## Version 5
Version 5 Modifications - Slots added to rear wing end plates and updated diffuser.

<img width="710" height="194" alt="image" src="https://github.com/user-attachments/assets/06a38611-b236-44d2-8cbd-bf11e5e832d7" />

Version 5 Quantitative Data and comparison with Baseline

<img width="316" height="104" alt="image" src="https://github.com/user-attachments/assets/eb9f8d7e-42b0-4494-8a46-8c0911771493" />
<img width="335" height="127" alt="image" src="https://github.com/user-attachments/assets/4a114afa-ecd5-4cd0-8ef0-cde975b99d85" />


Version 5 Eng Plate Wake Comparison - The addition of the slots allows higher pressure airflow to pass through the end plate, reducing the size of the wake in the low-pressure area.

<img width="381" height="245" alt="image" src="https://github.com/user-attachments/assets/57b1cebe-7945-484a-be2e-ba4495593022" />

Version 5 CPz Comparison - Version 5 shows a much larger single red area, indicating more negative lift being produced.

<img width="258" height="214" alt="image" src="https://github.com/user-attachments/assets/132ae21e-81f4-47db-b4b2-35b85ac07d2f" />

Version 5 Diffuser Velocity Plane Comparison - The extended end fences on Version 5 prevent the tyre wake from being injected by the diffuser, freeing up airflow from the floor and improving the efficiency of the diffuser.

<img width="302" height="197" alt="image" src="https://github.com/user-attachments/assets/33bdb1e6-14d6-40eb-8d90-4036673a6290" />

## Tools & Skills Demonstrated
* CFD simulation (Star-CCM+)
* Aerodynamic analysis
* Mesh generation and refinement
* Post-processing and flow visualisation
* Catia V5 Surface Design

## Files

* Full Dissertation Report - https://livecoventryac-my.sharepoint.com/:b:/g/personal/abbisst_cu_coventry_ac_uk/IQCN_s8VuV_ER7RFFMuColqzAbdL_895nDgiif2xpu71x0A?e=K7DB01

