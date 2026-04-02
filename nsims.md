---
layout: page
title: Numerical Simulations
permalink: /research/nsims/
sidebar_exclude: true
---

<p>Numerical simulations are a powerful tool to constrain galactic winds. You'd be surprised to know how much we can learn about gas in galaxies 
with Euler equations, which essentially conserve mass, energy, and momentum for fluids. 
</p>

The basic setup of all my simulations is:
<!-- `Initial Conditions` + `Equations of Conservation` -->
<div style="text-align: center; margin: 20px 0;">
  <img src="{{ '/assets/nsims-schematic.png' | relative_url }}" 
       alt="Galaxy Simulation" 
       style="max-width: 80%; border-radius: 8px; border: 0px solid #ddd;">
  <p style="font-size: 0.9em; color: #666; font-style: italic;">
  </p>
</div>

<h3> Insight #1: All SN are alike. But every galactic wind is launched in its own way. </h3>

<p>How we add SN in our simulations substantially changes the properties of galactic winds, which in turn changes how they are observed. 
In <a href="{{ site.data.papers.v2018 }}">first PhD paper</a> I showed how adding SN to the centre vs distributing them across the disc of the galaxy produces very distinct structure of galactic winds.
of the galaxy </p>

<div style="text-align: center; margin: 20px 0;">
  <img src="{{ '/assets/di-ci.png' | relative_url }}" 
       alt="Galaxy Simulation" 
       style="max-width: 80%; border-radius: 8px; border: 0px solid #ddd;">
  <p style="font-size: 0.9em; color: #666; font-style: italic;">
  Distributing SN (left) produces multiphase galactic winds while adding them at the centre, like a nuclear burst (right), launches smooth winds.
  </p>
</div>

<h3>Insight #2: Galactic winds shape metallicity of galaxies. </h3>
My series of papers with <a href="https://quokka-astro.github.io/quokka/about/"> QUOKKA </a> code explores how galactic winds carry metals deposited
by SN. Nearly half of the metals released in SN explosions are lost in the hot phase of galactic winds. 

<h3>Insight #3: Environment shape galactic winds. </h3>

A <a href="{{ site.data.papers.qediii}}">systematic study</a> of galactic winds links their kinematical properties, viz their loading factors, with 
the environment from which they are launched. 

<p style="font-size: 0.85em; font-style: italic; line-height: 1.1; margin-bottom: 5px;">
  <a href="https://www.youtube.com/watch?v=0CGVgAYJyjk" target="_blank" style="color: inherit; text-decoration: none;">
    I could be cold, I could be hot,<br>
    I could be metally high,<br>
    I could be fast, I could be slow,<br>
    I could be anything you like.<br>
  </a>
</p>

[Back to Research](/research/)