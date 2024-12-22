# Tailwind CSS Gradient Background Issue

This repository demonstrates a strange issue with Tailwind CSS gradient backgrounds.  Under certain color combinations, the gradient renders unexpectedly.  The `bug.js` file shows the problematic code, while `bugSolution.js` offers a potential workaround.

## Problem
The gradient background using `bg-gradient-to-r from-blue-500 to-purple-500` appears distorted in some browsers or contexts. This inconsistency may result in visual bugs that need addressing for cross-browser compatibility.

## Solution
The solution involves specifying more precise color values or using a different gradient approach to achieve better consistency.