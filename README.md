# Goal
This tool is meant to Merge and Superimpose plots from DQMData.

![goal](https://raw.githubusercontent.com/imKuehlschrank/GuiPlotTool/master/doc/img/goal.png)


# UI Overview

![UI Overview](https://raw.githubusercontent.com/imKuehlschrank/GuiPlotTool/master/doc/img/guiOverview.png)


# Example Workflow

Let us assume we are interest in the 'on track clusters of TID PLUS' in the rings 1,2, and 3.
We start by opening the run file in which we are interested.

![Load Dialog](https://raw.githubusercontent.com/imKuehlschrank/GuiPlotTool/master/doc/img/loadDialog.png)

The ROOT file has been loaded. The List Area should now contain lots of files. You can take a quick peek at one of the files by double clicking it, which puts it in the Current Selection Area. Click the 'Preview List' button to show a plot a the current selection.

![Preview](https://raw.githubusercontent.com/imKuehlschrank/GuiPlotTool/master/doc/img/preview.png)

To remove the file from the current selection just double click it.

Now we will make use of the quicksearch box at the top. Type "OnTrack__TID__PLUS__ring__" to filter the List Area.

Selecting the "Display Path" checkbox enables us to see the complete file names of the plots. We see that it is not actually duplicates but files that are in the 'Reference' folder and the 'Current Run' folder.
Select all the plots.

Check 'Pub. Style', 'Show stats', 'Show legend', and 'Use Custom Title', and enter the string 'My Cool Plots' in the text field.
Click on 'Superimpose'. To change the legend text right click on the legend's text you want to change and select 'Set Entry Label' and enter it there.

![Superimpose](https://raw.githubusercontent.com/imKuehlschrank/GuiPlotTool/master/doc/img/superimpose.png)

You successfully compared the plots of the reference run to the current run.

Well done.
