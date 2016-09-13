# Standard Operating Procedure for Habitat Annotation using TransectMeasure

<HR>
</HR>

<b>Table of contents</b>

[Load images and attribute file](#transectmeasure)<br></br>
[Setting and overlaying the grid](#method)<br></br>
[Classifying the habitat in an image](#classifying)<br></br>
[Saving and exporting from TransectMeasure](#transectmeasure-export)<br></br>
[Bibliography](#bibliography)

<HR>
</HR>

#<a name="transectmeasure"></a>Load images and attribute file

1)	Open the program “TransectMeasure” and you will be welcomed with a blank screen. 

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273095/354953a4-746e-11e6-995d-1561c5411a44.jpg "TransectMeasure")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


2)	To start an analysis for a new set of images: “Measurement” > “New measurement file” <b>OR</b> select “Read from file ...” if you are working from a previously saved TMObs* (see ‘Saving and exporting from TransectMeasure’ further down). 

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273107/433d9010-746e-11e6-80be-63de6a1c3f29.JPG "New Measurement file")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>
*TMObs, TransectMeasure Observation File


3)	Locate the folder where your images have been stored: “Picture” > “Set picture directory ...”

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273145/7a51fdca-746e-11e6-8dc1-4acd8acfbf8f.JPG "Set picture directory")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


4)	Load the first image to be analysed: “Picture” > “Load picture ...” (see above). 
- Retake habitat images if they are unfocused and blurry or when visibility is low.


5)	To load the attribute file containing all of the CATAMI habitat classification codes: “Measurements” > “Load attribute file ...” > The attribute file is a text file containing the information necessary for populating the drop down tabs when classifying your image. 

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273154/8d3c72b2-746e-11e6-9b84-cac36a2f786d.JPG "Load attribute file")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>

<HR>
</HR>

#<a name="method"></a>Setting and overlaying the grid

1)	To set up the grid: “Measurements” > “Dot configuration ...” > Set accordingly - Gridded dots, Dots across images = 5, Dots down image = 4 and check the “Overlay rectangles” box. This will allow you to classify the habitat according to a 4 x 5 grid composed of 20 ‘rectangles’. You should only need to change these settings the first time you use the program on your computer. 

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273163/9b55b35e-746e-11e6-8eee-810ccc36150c.JPG "Set up the grid")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


2)	To overlay the grid: Right click on an image and select “Overlay dots”. The name of the image will then appear in the table to the left of the image. 

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273168/a5054a04-746e-11e6-8a1b-e80888eab9f4.JPG "Overlay grid")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273176/b00f08fe-746e-11e6-82f2-ab29094f7403.JPG "Overlay grid")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


<HR>
</HR>


#<a name="classifying"></a>Classifying the habitat in an image


1)	To classify each ‘rectangle’ in the grid: 

i.	Left click on a point in the middle of a ‘rectangle’ to display the “Attribute editor”.  

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273190/bfdf91b8-746e-11e6-9964-4c1c88deec09.JPG "Attribute editor")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>

ii. If you are using:

<b>Standard (rapid) assessment</b> of Benthic Composition, Field of View and Relief we recommend using ONLY the:
BROAD/FieldOfView/Relief classes. 
OR

if you are using:

<b>Detailed assessment</b> of Benthic Composition (where coral bleaching or macroalgae compostion was of interest), Field of View and Relief we recommend using all the classes in the schema:
BROAD>MORPHOLOGY>TYPE/FieldOfView/Relief classes. 

iii.	Select the most dominant habitat from the “BROAD” dropdown (includes benthos*, un/consolidated substrate, open water** and unknown***) in the ‘rectangle’ that you selected, independently of all others in the grid (i.e. do not look across the whole image and decide that hard coral makes up at least one rectangle). 

<i>Note: Zoom into an image to analyse the habitat more closely by adjusting the "Zoom" value at the top left of the window before holding down the ctrl key and hovering your cursor over the area of interest. </i>

*Includes a number of broad types (e.g. Ascidians, Bryozoa, Crinoids)
**Accounts for parts of the image that are not benthos or substrate to calculate % coverage by habitat type. 
***Indistinguishable habitat when visibility is poor.

iii.	Continue to populate each dropdown (where possible) after “BROAD” (i.e. “MORPHOLOGY” > “TYPE” > “FieldOfView” > “Relief”). The “MORPHOLOGY” and “TYPE” drop down options will change depending on which “BROAD” option is chosen (e.g. dropdown levels are only provided for “FieldOfView” and “Relief” when “Open Water” is selected). Select “Clear” to reset the dropdowns for all of the categories.

iv.	“FieldOfView” (FoV) depends on how the BRUV is positioned when it lands on the substrate and is usually kept the same for every 'rectangle' in an image. The exception occurs when benthos or substrate obscurs a 'rectangle' within ~1m of the camera (typically the length of the diode arm on a BRUV). In this instance the "Limited" option must be selected for the obscurred 'rectangles' only.

Definition of FoV options:

<b>Facing Down:</b> No open water or fish visible.

<b>Facing Up:</b> No substrate or fish visible.

<b>Limited:</b> BRUV visibly landed on its side or the FoV is obstructed by benthos or substrate within 1m of camera (length of diode arm).

<b>Open:</b> BRUV landed upright and level on the substrate and there is an adequate amount of habitat available for classification.

<HR>
</HR>

The Relief class uses a 0-5 quatification of relief <sup>2</sup> and includes an "Unknown" level to account for 'rectangles' with a "Limited" FoV.

<i>When the “BROAD” category is “Open Water”, “Relief” should be classified as “Unknown”.</i>

“Relief” type is representative of structural complexity of substrate (angle and height) and relevant biota (e.g. high macroalgae is considered to create structural complexity in a habitat). Distinct categories have been adapted from Wilson et al. (2006):

<b>0.</b>	Flat substrate, sandy, rubble with few features. ~0 substrate slope.

<b>1.</b>	Some relief features amongst mostly flat substrate/sand/rubble. <45 degree substrate slope.

<b>2.</b>	Mostly relief features amongst some flat substrate or rubble. ~45 substrate slope.

<b>3.</b>	Good relief structure with some overhangs. >45 substrate slope.

<b>4.</b>	High structural complexity, fissures and caves. Vertical wall. ~90 substrate slope.

<b>5.</b>	Exceptional structural complexity, numerous large holes and caves. Vertical wall. ~90 substrate slope.


<HR>
</HR>

vi.	The dropdown for “CODE” is automatically filled by an eight digit code once all possible categories have been selected for that 'rectangle'. Codes are sourced from the CATAMI classification scheme and are dependent on the combination of the first three options selected (i.e. “BROAD”, “MORPHOLOGY” and “TYPE”). Please see below.

![alt text](https://cloud.githubusercontent.com/assets/14978794/18273210/d338f7e0-746e-11e6-929e-085d3f9f6c09.JPG "Attribute editor")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


2)	Continue to classify each 'rectangle' in the image until all 20 have been classified. To find any points not classified across one or all images classified: “Measurements” > “Show images with missing label attributes”.

3)	To easily access the next image to be classified: Select the arrow going forward in the box in the top left of the window. This may not work when the images have not been labelled in a numerical sequence. If this is the case, load the next image by going back to “Picture” > “Load picture ...”. 

![alt text](https://cloud.githubusercontent.com/assets/14978794/18274021/f92d276a-7472-11e6-8954-d1608ca211f3.JPG "Next image")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>

<HR>
</HR>

#<a name="transectmeasure-export"></a>Saving and exporting from TransectMeasure

1)	To save your work: “Measurements” > “Write to file ...” This creates a TMObs file where your habitat classification progress will be saved.

<i>For saving and operating purposes (TM tends to lag when >50 images have been analysed), load and save only 50 images per TMObs.</i>

![alt text](https://cloud.githubusercontent.com/assets/14978794/18274036/0c2f266a-7473-11e6-88d6-15310ffaa12e.JPG "Saving")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


2)	To export TMObs file: 
i.	 “Program” > “Batch text file output ...”

![alt text](https://cloud.githubusercontent.com/assets/14978794/18274045/1f6b387c-7473-11e6-9d65-4de84a0716a3.JPG "Batch output")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


ii.	The following box should appear: Double click to the right of the ✓ (under “Data”) in the “Input file directory” row, then locate the folder where your TMObs file has been saved > do the same for the “output file directory” to specify the folder location for saving your text file. Now select “Process”.

![alt text](https://cloud.githubusercontent.com/assets/14978794/18274059/322e1a2e-7473-11e6-968b-7493452084bd.JPG "Process")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>


iii.	Your habitat classification output (text file) should look something like this. Now you can use the R scripts provided in this repository to produce a tidy data set of % cover and mean and sd of relief for each sample.

![alt text](https://cloud.githubusercontent.com/assets/14978794/18274080/4ebf0f72-7473-11e6-8393-5ff2bd29ea88.JPG "Process")
<small>Screen capture from TransectMeasure (seagis.com.au) </small>

<HR>
</HR>

#<a name="bibliography"></a>Bibliography
1.Hill, N., Althaus, F., Rees, T., et al., 2014. CATAMI Classification Scheme for Scoring Marine Biota and Substrata in Underwater Imagery Version 1.4: December 2014
<br></br>
2.Wilson, S. K., N. A. J. Graham, and N. V. C. Polunin. 2006. “Appraisal of Visual Assessments of Habitat Complexity and Benthic Composition on Coral Reefs.” Marine Biology 151 (3). Springer-Verlag: 1069–76.
