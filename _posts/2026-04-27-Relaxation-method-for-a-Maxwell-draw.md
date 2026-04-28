---
layout: post
title: "Relaxation method for a Maxwell draw"
date: 2026-04-27
---

This is the electric potencial of the silhouette of a draw of James Clerk Maxwell, by the Relaxation Method.
As a way to solve Laplace equation, we can use the Relaxation Method to find a numerical solution.

<p align="center">
  <img src="/files/RM-Maxwell/PE2d.png" width="400">
  <img src="/files/RM-Maxwell/PE3d.png" width="500">
  <img src="/files/RM-Maxwell/Equipotenciales.png" width="400">
</p>

This solution take 683 s, and 82 iterations to compleate, in a grid of 198,025 points. This is done by the Gauss-Seidel method, and also by my own method of assign the inicial values of the potencial, before start the interations.
This own method make that the grid with the inicial potencial assigned, before the interations, look like this.

<p align="center">
  <img src="/files/RM-Maxwell/grid2d.png" width="400">
  <img src="/files/RM-Maxwell/grid3d.png" width="400">
</p>
