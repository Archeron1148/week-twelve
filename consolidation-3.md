>Discuss at least one ‘fail’ and one ‘win’. Explicitly situate your discussion with reference to the readings and annotations by the class as a whole. Again, as I asked at the end of Modules 1 and 2, in the context of the last few weeks, what has been most challenging win/fail for you, and why is that?

fail --> not participating week 11, overall not doing the really time consuming activities, seeing others' work is cool though

win -->

challanging --> artistic vs rational knowledge struggle

>Given what you’ve read and explored in this last module, which was about ‘communicating’ digital archaeology, what are the implications for ‘doing’ digital archaeology for different audiences? How has your thinking evolved since the end of Module 2? Are there new dilemmas that have emerged?

### Archaeology of the Heart



### Artistic Learning Through Doing

### Reproducability

Archaeological work is destructive by its very nature. When an artifact is removed from the earth it was found in it is no longer the same - an artifact can only be found one time. For this reason, the traditional scientific conception of reproducability cannot apply to archaeological phenomena, but once artifacts are abstracted into data and collected in databases, manipulations can be made on the data to bring out hiddel patterns or qualities which do not appear on the surface. Since data can be easily copied so that an original version remains undisturbed, these manipulations can be reproduced by simply following the same set of instructions on a fresh copy of the data in order to validate the results.

On a computer this reproducability is, in theory, as simple as copying the data and the code used to manipulate it, hitting 'run,' and comparing the results. In practice, its a little more complicated because of differences in machines and dependancy versioning: the same piece of python code may run differently depending on the machine and operating system it was compiled on, the version of python being used, and the versions of any libraries that have been imported. Any one of these things may have been the reason we failed in reproducing Hope Loiselle's findings.

Thankfully, there are strategies which can be used to mitagate a lot of these issues, i.e. keeping track of which versions of the dependancies were used as well as the specifications of the machine the experiment was run on. These version numbers and machine specifications along with the original data and the code to manipulate it can all be packaged together in a research compendium, which can then be used to recreate the same conditions (by using a virtual machine and downloaded the same dependacy versions) to validate the results of the experiment. [Ben Marwick et al. provide a very good article titled "Packaging Data Analytical Work Reproducibly Using R (and Friends)"](http://faculty.washington.edu/bmarwick/PDFs/Marwick-Boettiger-Mullen-2018-TAS-research-compendia.pdf) which explains the importance of using research compendiums and how to get started with creating one in R. But even so, putting together a research compendium is not a trivial task and there are still complications: we saw in week 10 how a tutorial for creating a research compendium no longer worked as intended because of some changes in its dependancies made over only a few months. 
