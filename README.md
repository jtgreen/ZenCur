# ZenCur

A simple model of hemorrhagic shock. 

See paper: 

Hemorrhagic shock model, code that reproduces major hemodynamic variables and graphs for second subject in the  in the paper: 
"A Simple Cardiovascular Model for the Study of Hemorrhagic Shock Luciano Curcio." 

Citation:
Curcio L, D'Orsi L, Cibella F, Wagnert-Avraham L, Nachman D, De Gaetano A. A Simple Cardiovascular Model for the Study of Hemorrhagic Shock. 
Comput Math Methods Med. 2020 Dec 24;2020:7936895. doi: 10.1155/2020/7936895. PMID: 33425003; PMCID: PMC7781723.

One parameter file necessary for loading initial parameters: 
opt_p0lv_kelv_v0lv_glower_control.mat

To run, have appropriate includes installed, then:

e = experiment()

e.plot()

All parameters from original paper.
