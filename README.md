# Projects Setup
<p>Repo for information on how to setup various platforms for development with my libraries</p>
<p><b>Note:</b> Not all projects require the libraries, but to keep everything simple, this should be followed for all of my projects.</p>
<ul>
<li><a href="#Windows">Windows</a></li>
<li><a href="#Linux">Linux</a></li>
<li><a href="#Mac">Mac</a></li>
</ul>

<h3 id="Windows">Windows Setup</h3>
<ul>
<li>
<h4>Install latest version of Visual Studio 2017 or greater <b>I DO NOT SUPPORT OLDER VERSIONS OF VS</b></h4>
<p>Download Community version: https://www.visualstudio.com/downloads/</p>
<p>Select the Desktop development with c++ and install</p>
</li>
<li>
<h4>Install cmake v8.2 or greater</h4>
<p><b>Download:</b> https://cmake.org/download/  <b>get the .msi file</b>, not the zip</p>
<p>Once downloaded, run the msi and press next to all of the dialog boxes that appear</p>
</li>
</ul>

<h3 id="Linux">Linux Setup (Ubuntu 16.04)</h3>
<ul>
<li>
<h4>Update existing tools</h4>
<p>Open a Terminal</p>
<p><b>Type:</b> sudo apt-get update && sudo apt-get upgrade -y</p>
</li>
<li>
<h4>Install tools and libraries</h4>
<p>Open a Terminal</p>
<p><b>Type:</b> sudo apt-get install build-essential python-dev git python-pip codelite libxext-dev libx11-dev libxfixes-dev libxinerama-dev gcc lldb libxtst-dev cmake-qt-gui -y</p>
<p><b>Type:</b> pip install autobahntestsuite</p>
</li>
<li>
<h4>Install cmake v8.2 or greater</h4>
<p><b>Type:</b> wget https://cmake.org/files/v3.8/cmake-3.8.2-Linux-x86_64.sh && chmod u+x cmake-3.8.2-Linux-x86_64.sh && sudo ./cmake-3.8.2-Linux-x86_64.sh --skip-license --prefix=/usr/local && rm cmake-3.8.2-Linux-x86_64.sh</p>
</li>
</ul>
<h3 id="Mac">Mac Setup</h3>
<ul>
<li>
<h4>Install latest version of xcode</h4>
<img src="https://raw.github.com/smasherprog/Projects_Setup/master/Mac/getxcode.JPG" height="200"/>
</li>
<li>
<h4>Install latest version of xcode command line tools</h4>
<p>Open a Terminal</p>
<p><b>Type:</b> xcode-select --install</p>
<p>Agree to the terms. Now the tools will begin to download and install</p>
</li>
<li>
<h4>Install cmake v8.2 or greater</h4>
<p><b>Download:</b> https://cmake.org/download/  <b>get the .dmg file</b>, not the tar.gz</p>
<p><b>Pre-Install:</b> Once you have successfully downloaded the .dmg file, simply click on it and press Agree at the next window<p>
<img src="https://raw.github.com/smasherprog/Projects_Setup/master/Mac/cmakedmg.JPG" height="200"/>
<p><b>Install:</b> To complete the installation you must drag and drop CMake onto the Applications folder.</p>
<img src="https://raw.github.com/smasherprog/Projects_Setup/master/Mac/cmakeappinstall.JPG" height="200"/>
<p><b>Post-Install:</b> Close the previous window</p>
<ul>


