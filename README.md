# Probing Light Fermiophobic Higgs Boson via diphoton jets at the HL-LHC

[arXiv:2310.17741 [hep-ph]](https://arxiv.org/abs/2310.17741)

by Daohan Wang, Jin-Hwan CHO, Jinheung Kim, Soojin Lee, Prasenjit Sanyal, and Jeonghyeon Song

> __Abstract.__ In this study, we explore the phenomenological signatures associated with a light fermiophobic Higgs boson, $h_f$, within the type-I two-Higgs-doublet model at the HL-LHC. Our meticulous parameter scan illuminates an intriguing mass range for $m_{h_f}$, spanning $[1,10]\,\text{GeV}$. This mass range owes its viability to substantial parameter points, largely due to the inherent challenges of detecting the soft decay products of $h_f$ at contemporary high-energy colliders. Given that this light hf ensures $\text{Br}(h_f\to\gamma\gamma)\simeq 1$, $\text{Br}(H^\pm\to h_f W^\pm)\simeq 1$, and $M_{H^\pm}\lesssim 330\,\text{GeV}$, we propose a golden discovery channel: $pp\to h_f H^\pm \to \gamma\gamma\gamma\gamma\ell^\pm\nu$, where $\ell^\pm$ includes $e^\pm$ and $\mu^\pm$. However, a significant obstacle arises as the two photons from the $h_f$ decay mostly merge into a single jet due to their proximity within $\Delta R<0.4$. This results in a final state characterized by two jets, rather than four isolated photons, thus intensifying the QCD backgrounds. To tackle this, we devise a strategy within `Delphes` to identify jets with two leading subparticles as photons, termed diphoton jets. Our thorough detector-level simulations across 18 benchmark points predominantly show signal significances exceeding the $5\sigma$ threshold at an integrated luminosity of $3\,ab^{-1}$. Furthermore, our approach facilitates accurate mass reconstructions for both $m_{h_f}$ and $M_{H^\pm}$. Notably, in the intricate scenarios with heavy charged Higgs bosons, our application of machine learning techniques provides a significant boost in significance.


## VI. Machine Learning Approach for heavy $M_{H^\pm}$

In the previous two sections, we underscored the efficacy of our cut-based analysis strategy
in achieving robust significance values as well as the mass reconstruction of $m_{\gamma\gamma}$ and $M_{H^\pm}$.
Yet, challenges manifested when addressing the heavy charged Higgs boson. For instance, BP-6
reached a significance of 4.09, which is not convincing enough to confirm the presence of
the very light fermiophobic Higgs boson. Hence, in this section, we employ machine learning
techniques, with a keen focus on BP-6, BP-12, and BP-18, aiming to enhance the significances.
At the parton-level, the total cross sections for these benchmarks are $\sigma_\text{tot}(\text{BP-6}) = 9.62\,\text{fb}$,
$\sigma_\text{tot}(\text{BP-12}) = 9.63\,\text{fb}$, and $\sigma_\text{tot}(\text{BP-18}) = 9.83\,\text{fb}$.

For those interested in the datasets and the detailed operation of the deep learning model, we have made them available in [diphoton_jets_cnn.ipynb](diphoton_jets_cnn.ipynb).
