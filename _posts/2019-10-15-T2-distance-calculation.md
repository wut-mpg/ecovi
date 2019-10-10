---
layout: task
title: Camera geometry
category: lab
lab: 1
task: 2
brief: Measuring distance to known objects using camera intrinsics
---

## Important intrinsic equations

$$ u = f_x \cdot \frac{x}{z} + c_x $$

$$ v = f_y \cdot \frac{y}{z} + c_y $$

## Camera calibration and data acquisition

Calibrate camera of your phone (if you haven't already) as described in previous task. Take some pictures
of test object (that will be given to you). Take at least three photos, with object near, mid and far from
the camera.

## Task details

Use camera intrinsic parameters to calculate distance to test object. 

**Note**: In this task you are working with line lengths, not absolute object coordinates.
To get final equation for distance (*Z*) you have to modify intrinsic equations appropriately.

To measure pixel size of the object use `imtool` (available also as `Image viewer` in `Apps`.
