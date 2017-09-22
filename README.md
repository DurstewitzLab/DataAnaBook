# DataAnaBook
MatLab code for Springer book 'Advanced Data Analysis in Neuroscience'

This folder contains all MatLab (MathWorks, Inc.) code from
Durstewitz, D. (2017) Advanced data analysis in neuroscience: Integrating statistical and
computational models. Heidelberg: Springer.

All files are sorted into .zip folders according to the chapters within which they are first referred to
(implying that some data or code files may be required in later chapters as well). The prefix ‘MATL’
refers to MatLab wrappers (numbered according to the chapters they appear in) that may call one or
several more specific functions, and which produce the figures from the book – please see the book
cited above for more details.
If you decide to use some of the code in your own work, I would appreciate citation of the book
reference where appropriate.

For all comments, suggestions, notes on bugs or omissions, please email me at
daniel.durstewitz@zi-mannheim.de.
The original sources of the models and algorithms implemented are given and discussed in the book
above, but I also made an attempt to credit them directly within the MatLab files where appropriate
(except for standard textbook methods); please send me an email in cases where you feel I might
have missed or overlooked something. I will try to continuously update the files and comments
within them.

I am thankful to Drs. Emili Balaguer-Ballester, Georgia Koppe and Hazem Toutounji for
contributing MatLab code for kernel-PCA and linear state space models, respectively, and to Drs.
Matt Jones, Florian Bähner, Christopher Lapish, Thomas Hahn and Helene Richter, among others,
for lending some of their experimental data as examples.

Some of the routines require additional toolboxes or software to run from other authors:
- In MATL6_3.m, the LLE code by Roweis & Saul, 2000, www.cs.nyu.edu/~roweis/lle/code.html,
and the MatLab code for Isomap from Tenenbaum et al., 2000, http://isomap.stanford.edu, is
required.
- In MATL8_2.m, the MVNHMM toolbox by S. Kirshner,
www.stat.purdue.edu/~skirshne/MVNHMM, is needed

All code within this folder is distributed under the terms and conditions of the GNU General Public
License vers. 3.
