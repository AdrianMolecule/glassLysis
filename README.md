# glassLysis


The link to the main document is: https://docs.google.com/document/d/1BRZD6a2Xy3QKFjnbU9aNmwXgNiaaAhemgtZ4K4PGWkg/edit?tab=t.0

Below is an older version I keep in case the document at the link gets lost somehow.

This project is about cell lysis using an oscillating tool.
I'll be using this to lyse cells to recover DNA, maybe RNA and Proteins.

It's designed as a very affordable solution to a sonicator. The oscillating tool costs about 45$ new and you might be able to get a used one for half the price especially if it comes with used or broken blades. You don’t need blades.

It is well known that cell lysis can be achieved by using glass beads and a vortex. The problem with that besides the fact that Vortexes can be more expensive is that it is slow and more importantly it seems to depend on how you hold the tube.

The oscillating tool solution is very fast and since the tubes are attached to the blade it can yield consistent results. Oscillating tools are very noisy so better use some ear protection.

The duration could vary depending on the cell types. Below I collected some info regarding other protocols using the vortex.

My first try will be with pork cells so probably will work with most mammalian cells. It’s for DNA extraction more precisely mitochondrial DNA.
I will use nail glass beads .5 to 0.8 mm
I have not tested this but I’m sure it will work. I will try 2 cycles and vary the duration. In principle too little will leave too many intact cells, too much might shear the DNA too much. I will use the higher speed setup on the machine and that is 5 and means 20000 oscillations per minute according to the manufacturer. I use a Mastercraft brand for no particular reason except that I have one.

I will put here several model files and most of the important dimensions are parametric.
I printed 2 of the models in plastic:
	First mounts on an existing blade and requires you to drill 2 4 mm holes in the blade. It’s hard to drill in the blade. You will also need 2 screws and nuts to attach that to the blade. Make sure they are long enough.
	The second I printed in ABS plastic and mounts as a blade. No need to drill or need screws but it might work or not with your blade pattern. Most patterns are common.
	Third one is similar to the second one but is cut in metal and you need to bend it to hold 2 tubes. I’ll cut that in metal ~2 mm thick using a plasma CNC of a friend

I will add both Fusion360 files and stl files for 3d print and .dxf for plasma cutter



My protocol:
TIME: 2 cycles of 3 min leave on ice in-between, let's vary this 2 times
Glass beads: used nails decoration glass beads. I tried them and they don’t seem to break into smaller pieces during the procedure.
Quantity: about 1/3 of the tube or .7 grams beads for a centrifuge tube
BUFFER: Tris-HCl buffer (pH 8)
Supported Containers: standard centrifuge tube and 2 ml plastic 11 mm diameter..
empty 1.5 ml eppi tube=.834 g, full with beads =2 grams. So that’s how we can calculate weight /volume ratio for my glass beads


=========================================================
===Below are unordered links and excerpts from the Internet that offer information about protocols =========
https://www.researchgate.net/post/Can_I_use_05_mm_glass_beads_for_cell_disruption_of_E_coli
glass beads for cell disruption
You can easily use 0.5mm beads with a bead to liquid sample ratio of 1:5 and 5 cycles of 30 sec ON and 20 sec OFF unless it is a membrane bound protein.

One can use glass beads for cell disruption (0.5 mm; vortex 8x for 20s, with intermediate keeping the eppis on ice for 1 min); but you should be aware that it might change the properties of your expressed protein. We have tested in our lab different cell disruption methods and luckily in our case the protein did not show huge differences in stability or binding to resin properties.

"I decided to go crazy with it and try a ratio of 1.5g beads to 1ml cell suspension. I had about 10ml total divided into 6 tubes so that each was only 1/2 full.  I used a bead beater for 20 min total 3 tubes at a time switching resting on ice in 2 minute intervals. I will take your advice for next time to not beat for so long. It sounds like my way was overkill but luckily the enzyme survived. 	
https://cellcrusher.com/protocols/yeast-lysis-with-glass-beads-and-a-vortexer/

Problems associated with disruption of yeast, fungus or algae using glass beads      
The old approach of manually holding a tube of beads and cells on a vortexer is somewhat effective for small samples of yeast.  Minute samples (e.g. 0.1 g) for DNA analysis can be disrupted in microcentrifuge tubes, shaken on a vortexer, this generally yields good results, as (a) the amount of DNA needed is usually not very large and (b) the narrow diameter of the microcentrifuge tube helps create a vigorous vortex.

Slightly larger scale cell disruption (up to 1 g wet weight) for protein work in 15 ml centrifuge tubes is possible using a vortexer, if temperature control and labor are not key concerns.  However, it is our experience that attempting to scale up this approach by using bigger samples in 50 ml centrifuge tubes yields very poor results.  The wider diameter of the 50 ml tubes produces much slower agitation and therefore slower cell disruption, while simply adding bigger

https://2013.igem.org/Team:Calgary/Notebook/Protocols/GlassBeadsCellLysisProtocolforProteinSamples
In a 1.5mL tube, add ~0.5mL of glass beads and 1mL of cells resuspended in lysis buffer.
Leave on ice for 5 min. Leave on BeadBeater or Vortex for 5 min. Repeat this cycle 2 times.


https://www.colorado.edu/lab/odorizzi/sites/default/files/attached-files/glass_bead_lysis_of_whole_cells.pdf

https://www.mdpi.com/2076-3417/12/2/648
https://link.springer.com/article/1li. The efficacy of a simple laboratory method for cell disruption based on the shaking of glass beads on a rotary shaker was assessed in this study, via measurements of the release of total protein and interferon-α2b from E. coli. The optimum conditions for cell disruption were detected after 30 min of shaking in Tris-HCl buffer (pH 8) at 300 rpm with 1.5 g of glass beads (diameter: 0.5 mm) per mL of cell suspension volume. Three test runs were conducted under the above conditions and the maximum average protein release values were determined as 3.048, 3.564, and 3.015 mg/mL, respectively. The amount of protein release was comparable to the amount of protein release in ultrasonica-tion and glass bead vortexing procedures. The amount of interferon-α2b release in the ultrasonication, glass bead vortexing, and glass bead shaking trials were 240, 172, and 201 ng/mL, respectively. This method was shown to process between 1 and 10 mL of sample volume in a 50 mL Falcon tube without a great deal of deviation, and was able to handle in excess of 60 samples simultaneously.

https://theanalyticalscientist.com/fileadmin/tas/issues/App_Notes/102-0016-retsch-app-note-an_cell_disruption.pdf	

my nail beads 13/cm .5 to 0.8 mm


1:5 and 5 cycles of 30sec ON and 20sec 2.5 minutes
30 min of shaking in Tris-HCl buffer (pH 8) at 300 rpm with 1.5 g of glass beads (diameter: 0.5 mm) per mL 30 min
in a 1.5mL tube, add ~0.5mL of glass beads and 1mL of cells resuspended in lysis buffer.
Leave on ice for 5 min. Leave on BeadBeater or Vortex for 5 min. Repeat this cycle 2 times - 10 min total
1.5g beads to 1ml cell suspension









