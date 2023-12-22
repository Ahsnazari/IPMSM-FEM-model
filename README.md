# IPMSM-FEM-model
A FEM model of IPMSM using Maxwell Software

Interior Permanent Magnet Synchronous Motor (IPMSM) is a type of AC synchronous motor that has its permanent magnets buried inside of rotor in contrast to the traditional Permanent Mganet Synchronous Motor (PMSM) which has permanent magnets mounted on the surface of the rotors. This unique design provides several advantages to the IPMSM, including high power density, high efficiency and a wider range of speed.

In this project a 4 poles, 3phase IPMSM is modelled. Rotor and Stator are designed using M19 steel sheet material and 4 permanent magnets of type NdFe36 are placed inside the rotor. 

Using Maxwell 2d, a physical model is constructed as shown in the figure below, where phase A is shown with the color orange, phase B and C respecively with the colors blue and green. The four permanent magnets used in this projects are highlighted with red and yellow colors inside the rotating part.


![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/37e99579-5b23-47c1-8e19-dfdbb13b01dd)

This is how the flux lines form during the rotation:

![flux lines](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/081bb9a8-567a-4394-8ce4-91dab08e7ca3)

The magnetic field:

![B](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/4687a4b8-28c0-472c-bc26-fe3e09b90aa3)

The average and max torque during simulation time: 

![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/c0c5d419-2f50-4f4f-92e3-2fdb71a50497)

The steady state self-inductance of phase A and mut. induction of phase A regarding to B and C:

![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/a33e66ab-4454-4dd0-a5b3-492689e03b28)

Flux linkages:

![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/eae9d024-c2ba-42c9-8dfe-55298cf6ddf1)

Comparison of Induced voltage and input voltage:

![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/feea8bb7-10ce-4fe2-9cfd-586401d9aed3)

Core loss:

![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/62dad484-b723-4da8-9ab2-391f4325a98b)

Optimizing the PM length from 50 to 65 mm:

![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/a1f46d3f-0c3f-4bd8-b979-a223abd0589e)

which goes to show 65mm is the optimal length of PMs. However the coreloss slightly increases:

![image](https://github.com/Ahsnazari/IPMSM-FEM-model/assets/118515566/d02ecbf6-c4b3-4b7b-859b-f96742c8b120)







