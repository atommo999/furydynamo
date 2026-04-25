# furydynamo
Inspired by the research paper by Thierry Alboussière, Franck Plunian and Marc Moulin: "Fury: an experimental dynamo with anisotropic electrical conductivity". A design concept for creating such a dynamo.

Research paper: https://royalsocietypublishing.org/rspa/article/478/2268/20220374/82516/Fury-an-experimental-dynamo-with-anisotropic

The design here is for the rotor and stator- the enclosure will need to be designed separately. Refer to the research paper for ideas. Some tips:

The housing typically follows this "sandwich" architecture:

<h3>The Outer Cylinder (The Jacket)</h3>

The stator itself often acts as the primary inner wall, but it is slid into a Stainless Steel 316 outer sleeve. 

<b>Purpose:</b> Since Galinstan is incredibly heavy (density approx 6.44g/cm^3), the outer sleeve prevents the copper stator from deforming under the centrifugal pressure and the weight of the fluid. 

<b>Insulation:</b> The stator's outer surface must be insulated from the steel jacket (often with a thin Kapton tape or epoxy layer) to ensure the current follows the copper grooves  rather than shorting through the steel.

<h3>The End Caps (The Seals)</h3>
This is the most critical part of the container. You need two heavy-duty steel plates bolted to the ends of the stator assembly.

<b>Drive Side:</b> Contains a hole for the rotor shaft. This requires a high-speed mechanical seal or a double O-ring setup to prevent Galinstan from spraying out at 1500+ RPM.

<b>Dead Side:</b> Usually solid, housing a bearing to support the other end of the rotor shaft.

<b>Expansion Chamber:</b> Galinstan expands when it gets hot from friction. The container usually has a small reservoir or "header tank" at the top to allow for volume changes without blowing the seals.

<h3>The Galinstan "Fill Path"</h3>

To visualize the container, you have to picture where the Galinstan actually goes:

<b>The Grooves:</b> The 20 rotor grooves and 23 stator grooves must be completely flooded. The Gap: The 1 mm space between the components. The Vacuum Purge: The container should have two ports: one at the bottom for filling and one at the highest point. Crucial Step: You must pull a vacuum on the container before injecting the Galinstan. If air bubbles are trapped in your 23 stator grooves, the electrical path will be broken, and the dynamo will never "start."
