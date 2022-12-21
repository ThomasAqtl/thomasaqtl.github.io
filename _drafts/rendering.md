---
layout: post
title:  "About rendering objects"
math: true
---

# Introduction

In order to understand the way computer *renders* images on a screen, we first have to think about an elementary problem. When drawing an object on a piece of paper using a pen, we can either imaginate a scene, or use an existing one as a model. We can even mix those and get inspired by reality to create something new. A computer, however, cannot work this way. It needs specific data to be able to properly *draw* them on your screen. But what are these *data* ? This question could be asked in many different forms, but more formally : how can we represent any object in a computer ?

# Coordinate system

The most fundamental building block of any scene is a *coordinate system*. A coordinate system is a tool that allows to define **specific positions** in space.