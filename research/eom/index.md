---
layout: default
title: Calculating excited states in solids
---

One very important aspect of practical applications and theoretical
developments in solids is the accurate study of excited electronic states.  We
are interested in accurately treating systems like colour centers in solids and
excited state potential energy surfaces in chemical reactions.

In our group we aim to do this in the framework of the *Equation of Motion*
coupled cluster theory.

Similar to the usual coupled cluster exponential ansatz, i.e.,

$$
\left | \mathrm{CC} \right \rangle =
\exp \{\hat{T}\} \left | 0 \right \rangle
$$

where $ \left | 0 \right \rangle  $ is a single reference starting state
such as *Hartree-Fock*, the Equation of Motion Ansatz also involves an
operator $ \hat{R} ^{(i)} $ to create the $ i$-th excited state on top of the Coupled Cluster
ground state

$$
\left | i \right \rangle =
\hat{R} ^{(i)} \left | \mathrm{CC} \right \rangle
$$

The operator $ \hat{R} ^{(i)} $ is very similar to the $ \hat{T} $ cluster
operator,

$$
\hat{R} ^{(i)} = r _{0}
               + r ^{a} _{i} \hat{c} ^{\dagger} _{a} \hat{c} _{i}
               + r ^{ab} _{ij} \hat{c} ^{\dagger} _{a} \hat{c} ^{\dagger} _{b}
                      \hat{c} _{i} \hat{c} _{j}
               + \ldots
$$

