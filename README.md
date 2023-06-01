# ENVS-193DS_homework-05

1. General Information

The data folder (data.hw5) contains an unzipped folder (knb-lter-hfr.109.18 (3)) which is made up of multiple files containing text and data related to the effects of prey availability on Sarracenia. The file most pertinent to our project is "hf109-01-sarracenia.csv", which contains the information for the 2005 Harvard Forest observations. We are only concerned with a few columns, specifically totmass, species, feedlevel, sla, chlorophyll, amass, num_lvs, and num_phylls. The observations were collected in 2005 from ten different species of sarracenia.

2. Data and File Overview

This README file gives an overview fo the files within the ENVS-193DS_homework-05 folder (a subset in the broader github folder). The Homework_5.qmd file contains the quarto markdown document which is the main document containing the code and short answers to the problem set. Additionally, there is a rendered document of the PDF version of the markdown (Homework_5.docx), both of which are in the "code.hw5" folder, a subset of the ENVS-193DS_homework-05 folder. Additionally, there is a folder called "data.hw5" (also subset of ENVS-193DS_homework-05) which houses a folder (knb-lter-hfr.109.18 (3)) containing data from the 2005 Harvard Forest experiment, notably the file "hf109-01-sarracenia.csv" which is used to test the hypothesis.

3. Sharing and accessing information

To access the the data used for the project as well as ancillary data, use the website https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-hfr.109.18. To acess the github of this project follow this link https://github.com/ethanblacher/ENVS-193DS_homework-05.git

4. Methodological information

Two plants of each Sarracenia species were allocated to one of six feeding levels in a regression design ranging from 0 to a quarter gram of finely ground wasps per feeding (for small sized species), 0 to half a gram (for medium sized species), and 0 to one gram (for large sized species). Plants were fed once a week for 7 weeks, with the above ground size and amass (mass-based light-saturated photosynthetic rate of youngest leaf) measured before beginning treatments. In total, the measurements contain twelve plants per ten different Sarracenia species, equaling 120 total plant observations. 


5. Data-specific information

The data included species-level identification ("species" column) along with many other measuremnets and calculations, of which we are only interested in a few, as enumerated in the "General Information" section of this README. Additionally, there is some missing data, most notably from the "chlorophyll", "sla", and "amass" columns.