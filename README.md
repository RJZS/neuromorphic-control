# Neuromorphic Control of a Pendulum

This readme provides the non-dimensionalised simulation parameters for the L-CSS/CDC submission 'Neuromorphic Control of a Pendulum'. The code itself will be uploaded in due course.

All simulations have $g_f^- = 2$ and $g_s^+ = 1.6$. The intra-HCO synapes have gain $g_\rm{syn,ij} = -0.2$ and the inter-HCO synapses have gain $g_\rm{syn,ij} = \pm 0.04$.

## Figure 2 - An HCO and its motor

$g_{us}^+ = 2.36$

We set $g_s^-$ to 1.05 for the lower burst size, and to 1.8 for the higher burst size.

## Fig 3 - Network Simulation

$g_s^- = 1.05$ and $g_{us}^+ = 1.75$

## Fig 5 - Overdamped Regime (Small Oscillations)

Top:       $g_s^- = 1.05$ and $g_{us}^+ = 1.73$

Middle:  $g_s^- = 1.35$ and $g_{us}^+ = 2.45$

Bottom: $g_s^- = 1.80$ and $g_{us}^+ = 3.52$

## Fig 7 - Underdamped Regime (Bistability)

 $g_s^- = 1.05$ and $g_{us}^+ = 1.75$

Initial conditions: $q(0) = 0$, $\dot{q}(0) = 0$ for large oscillations and $q(0) = 1, \dot{q}(0) = 0$ for small oscillations.

## Fig 9 - Phase Control

 $g_s^- = 1.05$ and $g_{us}^+ = 1.75$

## Fig 10 - Adaptive Control

Recall that the corrections $p_\omega$ and $p_A$ are proportional to the prediction errors. Note that the constant of proportionality was chosen differently for each simulation (that is, for each value of $A_\rm{ref}$).