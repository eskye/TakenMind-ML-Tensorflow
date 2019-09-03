Quick Note for MacOS and Linux Users
Hi Everyone!

Special note for MacOS and Linux Users, the tfdl_env.yml file may give you this error: 

ResolvePackageNotFound: - icu 57.1 vc14_0
Or something similar. If that is the case, I have created alternate environment files (.yml files) .

Link to alternate .yml file for MacOS Users:

https://www.dropbox.com/s/hoy95cr69z898no/mac_tfdl_env.yml?dl=0

Link to alternate .yml file for Linux Users:

https://www.dropbox.com/s/k4i3gmo0bvss7g7/linux_tfdl_env.yml?dl=0

Note: You don't need to sign up for dropbox, just click the "No Thanks, continue to view" button at the bottom, then go to the top right and click download. (I would have uploaded this direct to udemy, but .yml files aren't allowed).

Once you've downloaded that .yml file, just use it instead of the .yml file mentioned in the installation and setup lecture.

Alternative Option is to just download the few necessary libraries manually once you have Anaconda:

Step 1: Create an Environment

At the command line run:

conda create -n tfdeeplearning python=3.5 

Step 2: Install the libraries as you need them (there are only 6 you need to do). At the command line (with you environment activated) run the following:

conda install jupyter
conda install numpy
conda install pandas
conda install scikit-learn
conda install matplotlib
pip install --upgrade tensorflow 


If you encounter any other issues, please post to the QA forums and we'll help you out!

Thanks!

Jose and Pierian Data Inc. Team

