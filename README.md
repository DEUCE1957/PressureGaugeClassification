# The Vacuum Gauge project
This reposistory provides a number of interactive tools for investigating Vacuum Gauges at the Large Hadron Collider
 (LHC). These are provided in Jupyter Notebooks and - for convenience - should be hosted inside a [SWAN project](https://swan.web.cern.ch/). <br />
![Image of the Large Hadron Collider (LHC) at CERN](https://cds.cern.ch/images/CERN-PHOTO-201802-030-10/file?size=medium)

## Tools
* Analytical Vacuum Gauge Classifier <br /> 
<pre> Automatically detects coupling in provided Vacuum Gauge(s). </pre>
* Vacuum Gauge Explorer
<pre> Interactive tool for stepping through and plotting Vacuum Gauges</pre>
* Vacuum Gauge Main
<pre> Quick tool for plotting many Vacuum Gauges using wildcards</pre> 
* Single Gauge Analyzer 
<pre> Plot and save detailed info on a single gauge</pre>
* Vacuum Gauge Class Suite (WIP)
<pre> Object-oriented approach to Vacuum Gauge analysis, ideal for filtering </pre>
* Temperature Main
<pre> Tool for plotting thermometer readings for a specific fill </pre>
* Experimental Notebook
<pre> Testing ground for expermental features, use with caution</pre> 


## Using the notebooks
Running the .ipynb notebooks requires [Jupyter](https://jupyter.org/https://jupyter.org/) and [Python2](https://www.python.org/downloads/) to be installed. 
For ease of access, we recommend cloning this repository into [SWAN](https://swan.web.cern.ch/), which can be done directly
by using the <i> Download Project from Git </i> tool inside SWAN: <br/>
<pre> https://github.com/DEUCE1957/VacuumGauge.git </pre>
Please select a cluster configuration that has a Python2 kernel.

Otherwise you can setup your Python environment manually. We recommend using a virtual environment to isolate the 
requirements for this project.

<pre>
pip install virtualenv <br/>
$ ON LINUX $
pip install vitualenvwrapper  <br/>
source virtualenvwrapper.sh <br/>
$ ON WINDOWS $
pip install virtualenvwrapper-win
$ ON ALL %
cd YOUR-PROJECT-DIR/
mkvirtualenv vacuum <br/>
workon vacuum <br/>
pip install -r requirements.txt <br/>
</pre>
