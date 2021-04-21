OneKey, iOS Native UI
============================

This subdirectory implements an iOS native UI for OneKey.
It uses the 'Briefcase' project to create an Xcode project which contains within it a Python interpreter, plus all scripts and dependent python packages.  Python 3.6 or above is recommended.

- Rubicon-iOS Web Page: https://pybee.org/project/projects/bridges/rubicon/
- Briefcase Web Page: https://pybee.org/project/projects/tools/briefcase/

Quick Start Instructions
------------------------
1. Requirements:

   * MacOS 12.1  is required with Xcode installed
   * Python 3.8 must be installed
   * cookiecutter, briefcase, pbxproj, and setuptools python packages must be installed::
   * You must use 19.0.1 for pip

           python3.8 -m pip install 'setuptools==40.6.2' --user
           python3.8 -m pip install 'cookiecutter==1.6.0' --user
           python3.8 -m pip install 'briefcase==0.2.6' --user
           python3.8 -m pip install 'pbxproj==2.5.1' --user
           python3.8 -m pip install --user --upgrade pip==19.0.1  
           
2. Generate the iOS project using the included shell script::

   ./make_ios_project.sh

Additional Notes
----------------
The app built by this Xcode project is a fully running standalone OneKey as an iPhone app.!
