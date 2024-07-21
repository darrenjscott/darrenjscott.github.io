---
title: Physics research
layout: landing
description: 'Stuff I worked on..'
image: assets/images/board1.png
nav-menu: true
---

<!-- Main -->
<div id="main">

*<font size="3" color="GoldenRod">This is currently written assuming the reader has some familiarity with quantum field theory and the Standard Model. </font>*


<!-- SMEFT -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h2>Standard Model Effective Field Theory (SMEFT)</h2>
        </header>
        <p>
            The SMEFT augments the usual Lagrangian of the Standard Model with higher mass-dimension (non-renormalizable) operators. The idea being that a large class of new physics models which involve heavy new degrees of freedom, might give rise to these operators on top of the SM Lagrangian, once the heavy particles are integrated out. The high scale associated with the new physics, \(\Lambda\), is then captured in the Wilson coefficients of this (infinite) set of new operators. These operators are naturally ordered by their mass dimension since the Wilson coefficient associated to each operator is suppressed by inverse powers of the energy scale associated to the operator. Thus, if new physics lives at a scale of \(\Lambda = 2000 {\rm GeV}\), we might reasonably decide to start exploring operators which scale only as, say \(\Lambda^{-2}\) as compared to those which scale as \(\Lambda^{-4}\) and so, despite being confronted with an infinite series of operators, we have a natural order in which to investigate them.
        </p>
    </div>
</section>

<!-- SMEFT DETAILS -->
<section id="two" class="spotlights">
    <section>  
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Higgs decays</h3>
                </header>
                <p>
                One main focus of mine has been the calculation of the effects these operators might have on the decays of heavy bosons (most notably the Higgs) up to next-to-leading order (NLO) accuracy. Taking the most agnostic approach and making minimal assumptions we include the effects of any and all operators which could contribute to the decay process of the Higgs, including effects up to \(\Lambda^{-2}\) (so-called dimension-\(6\).
                After some early work, this culminated in the complete NLO results of Higgs decays to bottom quarks including all dimension-\(6\) effects (<a href="https://link.springer.com/article/10.1007/JHEP08(2019)173" target="_blank">Journal</a>, <a href="https://inspirehep.net/literature/1729733" target="_blank">inSPIRE-HEP</a>).
                We found the result to depend on a large number of coefficients once going beyond leading-order and were able to quantitatively show the relative weight of the Wilson coefficient associated with each operator, compared to the expected SM result. Along the way, we also explored some technical issues related to NLO calculations in the SMEFT, including the role of tadpoles, difficulties in renormalization of the electric charge (in the on-shell scheme), and Higgs -- Z boson mixing.
                </p>
            </div>
        </div>
        <div class="image">
            <img src="{% link assets/images/hbb_edit.png %}" alt="Higgs decaying to two b-quarks (blue), in ZH production. Detector graphic credit:CMS." data-position="top center"/>
        </div>  
    </section>
    <section>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Input schemes</h3>
                </header>
                <p>
                A more recent project involved the investigation of how the choice of input parameters in SMEFT calculations might affect the result, mostly paying attention to the types of Wilson coefficients which appear and how large the NLO corrections can be. We compared three schemes: \(\{M_W, M_Z, \alpha\}\), \(\{M_W, M_Z, G_F\}\), and \(\{G_F, M_Z, \alpha\}\). At least for the examples we chose to study, we found a large difference in the number of Wilson coefficients which appear beyond LO when switching between schemes, and studied the origin of these, not only between processes, but as a direct result of the renormalization of the input parameters themselves (and thus those which are universal and process independent). Furthermore, we saw that the largest NLO corrections arising from the scheme choice are actually universal, and can be effectively taken into account by some simple substitutions in LO results. The study further serves as a benchmark for comparisons of these schemes (at least for the results we studied) with full analytic and numeric results freely available with the article (<a href="https://link.springer.com/article/10.1007/JHEP07(2023)115" target="_blank">Journal</a>, <a href="https://inspirehep.net/literature/2657687" target="_blank">inSPIRE-HEP</a>).
                </p>
            </div>
        </div>
        <div class="image">
            <img src="{% link assets/images/input_scheme_art.png %}" alt="" data-position="top center" />
        </div>
    </section>
</section>

<!-- Three -->
<section id="three">
    <div class="inner">
        <header class="major">
            <h2>Resummation for top-quark pair production</h2>
        </header>
        <div class="image right">
            <img src="assets/images/ttbar_prod.png" alt="Top quark pair-production in hadron collisions" />
        </div>
        <p>
            Being the heaviest known fundamental particle so far discovered, studies of the top quark play an important role in testing the SM as well as investigating possible extensions of it. In particular, the production of top quark pairs, \(t\bar{t}\), at the LHC form a crucial part of these studies.
            Previously I have worked on projects involved in improving the accuracy of predictions based on the SM for the rate of top-quark pair production at the LHC. Specifically, we aimed to look at improving \(t\bar{t}\)-pair invariant mass distributions \(M_{t\bar{t}}\) (and later transverse momentum and rapidity distributions) by including resummation effects related to the emission of soft-gluons (threshold logarithms) and those related to a possible large scale hierarchy between the top mass, \(m_t\), and \(M_{t\bar{t}}\). We found that augmenting fixed order next-to-leading order (NLO) predictions (complete NNLO was not available at the time) with resummed results, leads to a radically different \(M_{t\bar{t}}\) spectrum as the energy of the \(t\bar{t}\)-pair increases. (<a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.202001" target="_blank">Journal</a>, <a href="https://inspirehep.net/literature/1417004" target="_blank">inSPIRE-HEP</a>)
            While working on the project, the complete and full next-to-next-to-leading order (NNLO) predictions were computed elsewhere. The group responsible for those calculations spent considerable time studying the choice of factorization and renormalization scale, ultimately advocating (on the basis of perturbative stability among other things) a choice which differed from a common previous choice. Working with this group, we were able to augment their results with our resummed predictions and further study the sensitivity to the previously mentioned scales in our resummed results. Our work showed that the effect of resummation on top of fixed order \(M_{t\bar{t}}\) predictions is to drastically increase the stability of the prediction with respect to the scale choice along with a slight reduction in theory uncertainties. Furthermore we were able to gain some insight into why the instability in scale choice can be reduced (<a href="https://link.springer.com/article/10.1007/JHEP05(2018)149" target="_blank">Journal</a>, <a href="https://inspirehep.net/literature/1663444" target="_blank">inSPIRE-HEP</a>).
            Beyond this, we also worked in combining these with electroweak corrections (<a href="https://iopscience.iop.org/article/10.1088/1674-1137/44/8/083104" target="_blank">Journal</a>, <a href="https://inspirehep.net/literature/1716558" target="_blank">inSPIRE-HEP</a>) and investigating effects on the rapidity distributions \(y_t\) and \(Y_{t\bar{t}}\) (<a href="https://link.springer.com/article/10.1007/JHEP03(2019)060" target="_blank">Journal</a>, <a href="https://inspirehep.net/literature/1704967" target="_blank">inSPIRE-HEP</a>[Journal]).
        </p>    
    </div>
</section>

<!--

     INCLUDE THESE AT SOME POINT
<img src="/assets/images/content/field_glow_1.png" align="left" width="200px"/>



---



<img src="/assets/images/content/ttbar_prod.png" align="right" width="250px"/>


-->

</div>