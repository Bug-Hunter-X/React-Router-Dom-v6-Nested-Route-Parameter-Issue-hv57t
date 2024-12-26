# React Router Dom v6 Nested Route Parameter Issue

This repository demonstrates a subtle bug in React Router Dom v6 when dealing with nested routes and route parameters. The issue causes unexpected rendering behavior, often resulting in blank pages or incorrect component display.

## Problem Description

When navigating to nested routes with parameters, the child route may not correctly receive or interpret the parameters, leading to rendering errors.

## Solution

The provided solution uses the `useParams` hook effectively to correctly access and use nested route parameters, ensuring the child components render the correct content.