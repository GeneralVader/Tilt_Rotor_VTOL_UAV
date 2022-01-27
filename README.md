# Tilt_Rotor_VTOL_UAV
This repository presents the conceptual design approach to a Tilt-Rotor Vertical Take-Off and Landing UAV with Unconventional Empennage Configuration. The configuration selection and other configurations of the UAV, were a result of background research and insights of commercially available VTOL UAVs. This model was designed for the **IIT Bombay TechFest event, AL-VTOLA**.

The model has been designed in _SolidWorks 2018_ and hence the SW part and assembly files will only open in the software of the same or later versions. STEP files have also been provided for people who'd like to use the model in previous version and/or in other CAD softwares.

![Screenshot 2022-01-15 142014](https://user-images.githubusercontent.com/77744383/150683885-a8afb7a4-0e1a-461b-87d3-1898fc0e904e.png)

## Introduction
Transitional Aircrafts are aerial vehicles that can perform as fixed wing aircrafts/UAVs, and also as a rotorcraft, by transitioning between these modes of flight when desired or needed. When TA operates in rotorcraft mode, it can hover, fly at low speeds in any direction (forward or sideways), perform some missions that are impossible or difficult for a fixed wing aircrafts like Aerial Photography or Surveillance, and also makes it possible for the aircraft to Vertically Take-off and Land (VTOL).

## Configuration Selection and Justification
1. VTOL Mode
Vyan takes off and lands vertically with the help of the four ducted propellers mounted on the twin boom, which in turn mounted below the wing. Once the UAV starts the transition, the front mounted propellers starts to tilt in the vertical plane, to provide the required horizontal thrust required for the cruise flight, and the rear mounted rotors are switched off in order to reduce the power consumption.
2. Wing
In order to avoid the protuberance, drag, a monoplane high wing configuration was chosen.
3. Empennage
Inverted 'V' Tail was considered to be apt for the transitional aircraft, considering the reduction of drag by almost 20% due to its less wetted area compared to conventional tails and 'T' Tails.
4. Fuselage
Design of the fuselage was done based on drag reduction, weight reduction while having enough compartment to mount wing, accommodate propulsion system, power plant, payload and electronic sensors to be used for surveillance. 

Below we discuss each component of the VTOL individually.

## Fuselage

![Screenshot 2021-12-22 180100](https://user-images.githubusercontent.com/77744383/151074906-46a9f97e-5f2c-4920-ac86-3ae771a3edff.png)

The fuselage was modelled according to the stringers and frame design with the latter joined and kept in place by the former. The frames are of balsa while the stringers have been kept of birch to provide strength to the model. The model was then covered by a skin. An aluminium landing gear as well as a camera and gimbal model has also been attached underneath the frame. A support has been provided for the attachment of the wing in the shape of the airfoil. 

![Screenshot 2021-12-24 233340](https://user-images.githubusercontent.com/77744383/151075297-bdacc8b4-6599-4cc0-86bc-155a6e24ddb9.png)

## Wing

![Screenshot 2022-01-26 044901](https://user-images.githubusercontent.com/77744383/151079067-bd989907-4d49-436f-9ae2-a931d09450bb.png)

The wing has been designed along the lines of ribs and spars model. The ribs have been assigned to be made of balsa and have several holes inside them to reduce weight while the spars are a combination of balsa, birch and carbon fibre as the weight of the wing had to be kept in check while also not compromising strength. Then the frame has been covered using solar film. The _Wortmann FX 73-CL2-152_ was chosen, after much analysis, as the wing's airfoil. The wing gets attached onto the supports provided on the fuselage and also has two circular supports on itself for the attachment of the twin-booms of the tail.

The wing has also been attached with Vortex Generators in order to inhibit stall and enhance recovery in case of one. It also increase lift and reduces drag on the wing. 

Space has also been provided for the attachment of ailerons onto rods controlled by a servo on the wing.

![Screenshot 2022-01-26 051225](https://user-images.githubusercontent.com/77744383/151079090-d044d24b-23e7-4e38-bec4-4bd3b35a4bfa.png)

## Tail

![Screenshot 2021-12-24 171643](https://user-images.githubusercontent.com/77744383/151079244-b6a735d5-221b-46a0-b768-6d8e75da964c.png)

The inverted V-tail configuration was selected for the tail, keeping the reduction of drag in mind. This was also modelled along the ribs and spars method with the ribs being of balsa and spars of birch covered by solar film. Two booms are attached on the either side of the tail that attach onto the holders provided on the wing. The rotors are also attached onto these booms. Control surfaces have also been provided on the tail, attached onto a servo driven rod.

![Screenshot 2022-01-27 050150](https://user-images.githubusercontent.com/77744383/151264542-71333448-6a15-44e7-a93f-69d59792accf.png)

## Tilt Rotors

An important component of the VTOL, the tilt rotor mechanism consists of a rod attached to a servo and a rotor hinge on either sides. The push-pull mechanism of the servo facilitates in changing the direction of the propellers. 


![Screenshot 2021-12-24 191028](https://user-images.githubusercontent.com/77744383/151265558-abcc5cf3-f734-4829-a86e-f509fa2fa264.png)

Ducted propellors of 10x5 measurements have been used in the design with two in the front and 2 behind the wing on either side of the fuselase.

![Screenshot 2022-01-14 223735](https://user-images.githubusercontent.com/77744383/151266911-48103323-ffc0-4c69-b13c-594e9dd499f4.png)


## Other Components

![Screenshot 2022-01-27 052810](https://user-images.githubusercontent.com/77744383/151267112-8075b8c7-a3eb-4f86-94ad-8b1f347f4aac.png)

A battery and a pixhawk have also been placed inside the fuselage, along with the camera, at the centre of mass of the VTOL, which essentially lies at the intersection of the diagonals of a square formed by the four propellors.

![Screenshot 2022-01-14 223735](https://user-images.githubusercontent.com/77744383/151267407-7b886d8e-ae5a-4c3a-b7d3-526fb31a7476.png)

## CAD Drawing


![Screenshot 2022-01-27 053847](https://user-images.githubusercontent.com/77744383/151267713-5d4e5c09-85bf-4bd4-bfd2-563659871257.png)


P.S.- The prototype folder contains some other fuselage and wing assembly files which were designed initially but were improved afterwards.
