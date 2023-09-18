<h1>Setting up a Professional Data Science Environment - Windows Installation</h1>
<h2>Introduction</h2>
<p>There are two major pieces we need to install in order to set you up for success as a professional data scientist! In this lesson, we will be installing Git and Anaconda for Windows.</p>
<h2>Objectives</h2>
<p>You will be able to:</p>
<ul>
<li>Install Git</li>
<li>Install Anaconda</li>
</ul>
<p>Let’s start by getting Git and Anaconda installed.</p>
<p>Please note - the exact names and versions will change over time.</p>
<h2>Installing Git</h2>
<h3>Overview:</h3>
<ol>
<li>Download the install package from <a href="https://git-scm.com/download/win" target="_blank">here</a>.<ul>
<li>If you do not know whether you need the 32 or 64-bit install, check your system type. On Windows 10, head to Settings &gt; System &gt; About. Under the Device specifications header, next to System type, you’ll see if Windows and your processor are 32-bit or 64-bit.</li>
</ul>
</li>
<li>Open the downloaded exe file<ul>
<li>You can either click the downloaded file at the bottom of your browser to open, or navigate to your downloads folder</li>
<li>It may open a window asking if you want to allow this application to make changes to your device, click “Yes”</li>
<li>Click “Next” to accept the license</li>
</ul>
</li>
<li>Select the installation destination<ul>
<li>The default option is recommended</li>
</ul>
</li>
<li>Select components<ul>
<li>Make sure to keep the “Windows Explorer integration” options checked</li>
<li>Otherwise, the default options are recommended</li>
</ul>
</li>
<li>Choose a default editor that you are comfortable with, or choose either Nano or Visual Studio Code if you have not used an editor before<ul>
<li>If you know or have used vi/vim, feel free to use it (otherwise it is not recommended)</li>
<li>You must have the editor installed to continue.  You can set a default now and change it later.</li>
</ul>
</li>
<li>Adjust the PATH environment<ul>
<li>Select “Use Git from the Windows Command Prompt”</li>
<li>The first option is also fine, as you’ll mainly be using Git from the new “Git Bash” program that is being installed, but the second option is ideal as it’ll give you the option of using it through either Git Bash or the Windows Command Prompt in the future if you wish</li>
</ul>
</li>
<li>Choose HTTPS transport backend. <ul>
<li>Select the “Use the OpenSSL library” option</li>
</ul>
</li>
<li>Configure line-ending conversions<ul>
<li>The default option is recommended</li>
</ul>
</li>
<li>Configure the terminal emulator<ul>
<li>Select MinTTY as the default terminal emulator</li>
</ul>
</li>
<li>Choose the default behavior of <code>git pull</code><ul>
<li>The default option is recommended</li>
</ul>
</li>
<li>Configure extra options to enable file system caching</li>
<li>Choose a credential helper<ul>
<li>Select Git Credential Manager</li>
</ul>
</li>
<li>Wait while Git is installed onto your computer</li>
<li>Click "Finish" to complete set-up<ul>
<li>It is not necessary to view the release notes</li>
</ul>
</li>
</ol>
<blockquote>It is <strong>strongly recommended</strong> that you select any options to install and use the "Git Bash" shell - it's generally included by default. The Git Bash shell will allow students with either Windows or Mac computers to run the same set of commands, and all commands in this program follow that convention.</blockquote>
<p>Note - if there are any differences in the options provided in the installer you download, accept the defaults.</p>
<h4>Git Installation Steps Step-by-Step:</h4>
<p>Step 1: Git’s download page for Windows OS - choose 32-bit or 64-bit option</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_download.png"/></p>
<p>Step 2: Open the downloaded file - on the license prompt, click “Next” to accept</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_license.png"/> </p>
<p>Step 3: Select the installation destination folder (default is recommended)</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_select_destination.png"/> </p>
<p>Step 4: Select components - keep the “Windows Explorer integration” options</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_select_components.png"/></p>
<p>Step 5: Choose the default editor - choose Nano or Visual Studio Code if you have not used an editor before</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_default_editor.png"/></p>
<p>Step 6: Adjust the PATH environment - second option is recommended</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_adjust_path.png"/></p>
<p>Step 7: Choose the HTTPS transport backend - choose OpenSSL library</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_https_backend.png"/></p>
<p>Step 8: Configure line ending conversions - select the default option</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_line_ending.png"/></p>
<p>Step 9: Configure the terminal emulator - choose MinTTY</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_terminal_emulator.png"/></p>
<p>Step 10: Choose “Default” as the default behavior of ‘git pull’</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_default_pull.png"/></p>
<p>Step 11: Configure extra options to enable file system caching</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_extra_options.png"/></p>
<p>Step 12: Choose Git Credential Manager as the credential helper</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_credential_helper.png"/></p>
<p>Step 13: Install</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_installation.png"/></p>
<p>Step 14: Installation Complete - Click "Finish" to exit Setup (do not need to view release notes)</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_git_complete.png"/></p>
<h3>Confirming Your Git Installation</h3>
<p>To confirm you have installed Git successfully:</p>
<ol>
<li>Open a terminal window<ul>
<li>When we ask you to use the terminal, we mean the Git Bash application we just installed through Git</li>
</ul>
</li>
<li>Type <code>git --version</code>: It should return the version of git you are running</li>
</ol>
<hr/>
<h2>Installing Anaconda</h2>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda.png"/></p>
<p>The easiest way to get set up with Python and Jupyter Notebook so you can start coding is to install the Anaconda distribution. </p>
<h3>Overview:</h3>
<ol>
<li>Download the latest version of Anaconda <a href="https://www.anaconda.com/download/#windows" target="_blank">here</a><ul>
<li>Same as with the Git installation - If you do not know whether you need the 32 or 64-bit install, check your system type.</li>
<li>A window may pop up asking if you want to give Anaconda your information in return for a cheat sheet - you do not need to do so unless you want to.</li>
</ul>
</li>
<li>Open the .exe file once it has downloaded to open the Anaconda installer<ul>
<li>Click "Next", then "I Agree" to accept the license</li>
</ul>
</li>
<li>Install for "Just Me"</li>
<li>Select the destination folder<ul>
<li>The default option is recommended</li>
</ul>
</li>
<li><strong>Choose both Advanced Installation Options</strong> <ul>
<li>Although you will see a warning from the installer, <strong><em>make sure</em></strong> to choose <em>both</em> "Add Anaconda to my PATH environment variable" <em>and</em> "Register Anaconda as my default Python" !!</li>
<li>For this program, these options will actually avoid you needed to uninstall and reinstall Anaconda in the near future, which is what they're warning about</li>
</ul>
</li>
<li>Wait while Anaconda is installed on your computer<ul>
<li>You can ignore any supplementary materials advertised, such as PyCharm</li>
</ul>
</li>
<li>When it thanks you for installing Anaconda, click "Finish"<ul>
<li>You do not need to learn more about your installation, and can close the browser window if one opens</li>
</ul>
</li>
</ol>
<h4>Anaconda Installation Step-by-Step:</h4>
<p>Step 1: Anaconda’s download page for Windows OS - choose 32-bit or 64-bit option</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_download.png"/> </p>
<p>Step 2: Open the downloaded file - on the license prompt, click “I Agree” to accept</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_license.png"/> </p>
<p>Step 3: Select “Just Me” for Installation Type</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_just_me.png"/> </p>
<p>Step 4: Select the installation destination folder (default is recommended)</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_install_location.png"/> </p>
<p>Step 5: <strong>Make sure to choose both Advanced Installation Options!</strong></p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_advanced_options.png"/> </p>
<p>Step 6: Installing Anaconda</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_install.png"/> </p>
<p>Step 6, Continued: You can skip any add-ons, like the PyCharm installation</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_pycharm.png"/> </p>
<p>Step 7: Installation Complete - click “Finish”</p>
<p><img src="https://curriculum-content.s3.amazonaws.com/data-science/images/win_anaconda_finish_install.png"/> </p>
<h3>Confirming Your Anaconda Installation</h3>
<p>To confirm you have installed Anaconda successfully:</p>
<ol>
<li>Open a terminal window</li>
<li>Type <code>conda info</code>: It should return a table of details about your conda installation</li>
</ol>
<h2>Summary</h2>
<p>Congratulations! If you've gotten this far and everything has worked, you have successfully installed Git and Anaconda on your Windows PC! </p>