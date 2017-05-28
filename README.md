# Projects Setup
Repo for information on how to setup various platforms for development with my libraries
<p>Goto</p>
<ul>
<li><a href="Windows">Windows</a></li>
<li><a href="Linux">Linux</a></li>
<li><a href="Mac">Mac</a></li>
</ul>
<h3 id="Windows">Windows Setup</h3>

<h3 id="Linux">Linux Setup (Ubuntu)</h3>

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
<h4>Install cmake v8.1 or greater</h4>
<p><b>Download:</b> https://cmake.org/download/  <b>get the .dmg file</b>, not the tar.gz<p>
<p><b>Pre-Install:</b> Once you have successfully downloaded the .dmg file, simply click on it and press Agree at the next window<p>
<img src="https://raw.github.com/smasherprog/Projects_Setup/master/Mac/cmakedmg.JPG" height="200"/>
<p><b>Install:</b> To complete the installation you must drag and drop CMake onto the Applications folder.<p>
<img src="https://raw.github.com/smasherprog/Projects_Setup/master/Mac/cmakeappinstall.JPG" height="200"/>
<p><b>Post-Install:</b> Close the previous window</p>
<li>
<h4>Install homebrew</h4>
<p>Open a Terminal</p>
<p><b>Type:</b> /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"</p>
<p>You will be prompted to press ENTER to continue --which you should.<p>
<p>Next you might have to enter your password. If prompted, enter your password</p>
<p>At this point, homebrew is installed!</p>
</li>
<li>
<h4>Install homebrew common libraries</h4>
<p>Open a Terminal</p>
<p><b>Type:</b> brew install fltk boost openssl libjpeg-turbo zlib</p>
</li>
<ul>


