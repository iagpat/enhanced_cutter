Instructions for the Waveform cutter application

INSTALLATION
You need the file named WaveformCutter.mlappinstall. You need to click
on this file in a computer that has Matlab installed. You will be asked if
you want to add Waveform cutter to your apps. Click on yes.

After this step, the WaveformCutter app will appear within your "APPS" in 
Matlab.

HOW TO USE THE PROGRAM
Once installed, to start the program you just need to click on "WaveformCutter"
in Matlab. A window will pop up. Resize this window until you can see all the 
components of the program. Resizing does not work well in this application.

The upper left corner contains boxes and buttons to control the program. The
"Select a cluster #" option allows you to select a particular cluster to work 
with. This is the cluster that will be displayed on all graphs of the program.

The "Select a channel #" allows you to select a channel number to work with.

The button titled "Select .clu.1 file" allows you to choose a cluster file to
work with. This cluster file needs to be of type clu.1 and the other klusta 
files (res.1, spk.1, fet.1, xml) need to be in the same directory and have the same basename. 

The "Plot bins in radius" option allows you to modify the graph on the right 
named "Spikes from selected bins". This option is in miliseconds and it will
plot the spikes that have fired within the number of specified miliseconds from each other.

The options titled "Timepoint #", "Upper threshold" and "Lower threshold" are
used to select spikes that you would like to move to a new noise/other cluster. The
cluster number of the new cluster is specified after the text "Discarded spikes
will be placed in cluster number:". These three options move the three corresponding
axes on the two graphs of the right. To remove a spike, make sure it is in 
green (indicating that you have selected the right channel) and then make sure 
that the timepoint axe goes through the spike and that the upper and lower
thresholds are just above and just below the spike in that timepoint. Any
green spikes that are within the upper and lower thresholds in that timepoint
will be removed. To comfirm, click on "Cut spikes from waveform" to remove a spike
from the "Cluster waveform" graph or click on "Cut spikes from bin" to remove a spike
from "Spikes from selected bins". 

Make sure you click on "Save changes" before exiting the program to make sure that 
everything is saved.  

The lower left corner contains a cluster autocorrelogram. This histogram 
describes the number of spikes that fired within a specific number of 
miliseconds from each other. In the option "Histogram duration (ms)" you
can change the size of the histogram. That is the longest distance between
spikes you want to observe in the histogram.

The graph titled "Spike waveforms" plots spikes from the currently selected
cluster and for every channel. The "selected" channel will be displayed in
green and the other channels will be displayed in red. The channels are 
displayed in order of channel number. Only a number of spikes is displayed. 
This number is the batch size and it can be controlled on the option named
"Batch size". If batch size is 100 then up to 100 hundred spikes will be 
displayed. You can visualize more spikes by increasing the batch size or
by clicking on the Previous/Next buttons to navigate through all the spikes in
the cluster.

The graph named "Spikes from selected bins" is similar to the graph "Spike 
waveforms" but this one will only display spikes of that cluster that fired
within a specified number of miliseconds from each other. This number of miliseconds 
can be modified in the option named "Plot bins in radius".

There are two buttons above the graph to control the distance between each channel
in uV. By clicking on the + button the channels will appear closer together and by
clicking on the - button the channels will appear further away from each other.





















