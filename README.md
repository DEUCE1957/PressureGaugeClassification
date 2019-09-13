# The Vacuum Gauge project
This reposistory provides a number of interactive tools for investigating Vacuum Gauges at the Large Hadron Collider
 (LHC). These are provided in Jupyter Notebooks and - for convenience - should be hosted inside a [SWAN project](https://swan.web.cern.ch/). <br />
![Image of the Large Hadron Collider (LHC) at CERN](https://cds.cern.ch/images/CERN-PHOTO-201802-030-10/file?size=medium)

## Warnings
Tools are seperated into BackEnd and FrontEnd. To tweak behaviour across the board (e.g. Font-size on plots) modify the
BackEnd Files. however, be careful when making generalized changes as it may cause unintentded side effects in other parts
of the code. In general, it is recommended to stick to the FrontEnd files for normal usage.

The data directory is generated in a very specific hierarchy for easy traversal in many of the notebooks, hence do NOT
move or rename files in this directory unless you are well aware how the directory is being traversed.

## Tools
* Build Your Own Classifier <br /> 
<pre> Build any classifier from the Sklearn library using interactive responses</pre>
* XXXXXXXX_Classifier 
<pre> Notebook with classifiers settings predefined, essentially a worked version of the build-your-own classifier</pre>
* Vacuum Gauge Explorer
<pre> Interactive tool for stepping through, classifying and plotting Vacuum Gauges</pre>
* Raw Gauge Viewer
<pre> Plot single or multiple gauges using gauge_ids and wildcards</pre> 
* Data Collector
<pre> A simple tool for building huge datasets for unsupervised learning </pre>

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
