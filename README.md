This repository contains the KLO and corresponding SnapPy files used in the computation $\tau(J_0)=-1$. The following are the steps required to obtain the calculation.

In a SnapPy window type M=snappy.Manifold().

In the link editor window that gets opened, select File>Open File and choose your copy of `J0.lnk'. 

Then select Tools>Send to SnapPy, and go back to the SnapPy window. 

Type J0=M.link(); J0.knot_floer_homology().


Brief description of the files contained in this repository:

gamma0-bands-isotopies.klo: a KLO file showing the isotopies that transform gamma_0 into the diagram shown in Figure 5.

gamma0-remove_bands.klo: last diagram shows the link \gamma_0\sqcup\gamma_2\sqcup\gamma_3 with \gamma_2\sqcup\gamma_3 (blue & green curves) shown as a 2-component unlink.

gamma0-to-J0.klo: last diagram is the result of blowing down \gamma_2\sqcup\gamma_3.

J0.klo: stand-alone version of the last diagram from gamma0-to-J0.klo.

J0.lnk: the result of KLO>Export>diagram for SnapPea

J0.svg: a slight modification of the file created in SnapPy via File>Save Image>SVG








