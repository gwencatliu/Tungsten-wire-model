# Tungsten-wire-model
Mathematica notebook modeling a straight tungsten wire in an Argon gas, a constant heat transfer coefficient is assumed of 0.1

Modified from https://reference.wolfram.com/language/PDEModels/tutorial/Multiphysics/ModelCollection/JouleHeating.html 
In the following model the voltage drop across the tungsten wire is modified for values corresponding to our observations. The heat that generates in the wire is dissipated from the side surfaces by both thermal convection and radiation to the surrounding argon. The remaining heat propagates towards electrode pads at both ends and leaves the wire by thermal conduction. We assumed heat sinks in our model with the pads on ends to cool the wire down to the room temperature of 20+273.15 K. The heat transfer coefficient is assumed to be 0.1 in this example to give us overestimates of for convection loss that we wanted to reduce in our experiment.

The electric potential field  and the total heat generation  is simulated by an electrostatics model. Based on these result the temperature distribution  will then be modeled by a heat transfer model. Finally, the amount of heat loss through each surface is calculated and compared.

Made for Advanced Laboratory in Physics, Course Code Py581 at Boston University. 
