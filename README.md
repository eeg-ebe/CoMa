# CoMa
CoMa (short for Conspecificity Matrices) combines the partitions inferred from from independant sources of information (such as DNA sequences and morphology) into a single conspecificity matrix (Debortoli et al. 2016), the clustering of which reveals the number of species present among the samples analyzed.

# Installation

Just copy / paste this folder to a webserver.

If you want to use CoMa offline, either install a local webserver (recommended) or activate CORS requests so that the CoMa website can load its resources in the corresponding subdirectories
(this is not recommended as this has some security implications).

In order to activate CORS requests in Firefox, enter about:config as URL, accept the warning message and set the setting "privacy.file_unique_origin" to false.

# Usage

Open http(s)://&lt;name of your webbrowser&gt;/&lt;directory&gt;/index.html in any modern browser that fully supports HTML 5.

# Compilation

You also need to clone https://github.com/eeg-ebe/HaplowebMaker in order to cross-compile the haxe code into javascript code.

# Reference
Debortoli, Li, Eyres, Fontaneto, Hespeels, Tang, Flot, Van Doninck (2016) Genetic exchange among bdelloid rotifers is more likely due to horizontal gene transfer than to meiotic sex. Current Biology 26:723-732
