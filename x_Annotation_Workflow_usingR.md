# Annotation workflow using R 
Example workflow using R to format and calculate mean and sd rugosity and % habitat cover from Habitat annotation applied using the TransectMeasure software from www.seagis.com.au

<HR>
</HR>

<b>Table of contents</b>

[Example R script](#method)<br></br>
[Example data](#transectmeasure-example)<br></br>
[Folder structure](#introduction)<br></br>


#<a name="method"></a>Example R script

The example <a href="https://github.com/TimLanglois/HabitatAnnotation/blob/master/x_ExampleR_1_HabitatAnnotation_Format.and.write.data_160919.R">R script</a> is designed to import and format the raw annotation output from TransectMeasure and calculate mean and sd rugosity and % habitat cover.

The script uses Data Wrangling grammar from the tidyr and dplyr packages and data piplines.
For more information on the grammar of tidyr and dplyr see the <a href="https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf">Data Wrangling cheat sheet</a>. 


#<a name="transectmeasure-example"></a>Example data

An example of <a href="https://github.com/TimLanglois/HabitatAnnotation/blob/master/x_ExampleData_BRUV_TM_HabitatAnnotation.txt">habitat annotation data</a> generated from the TransectMeasure software is provided that will run with the above script.


#<a name="introduction"></a>Folder structure

The above script assumes that you have a folder strucutre following this format:

![alt text](https://cloud.githubusercontent.com/assets/14978794/18631738/5438d4a0-7ea6-11e6-83b4-9795445876b9.png "Example folder structure")

