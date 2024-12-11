# Next.js 15 App Router: Links Not Working

This repository demonstrates a bug encountered when using the new Next.js 15 App Router with the `next/link` component.  Links are not functioning correctly, failing to navigate as expected.  The provided solution addresses this issue.

## Bug

The `bug.js` file contains a simple component with two links, 'Home' and 'About', using the `next/link` component.  These links should navigate to '/' and '/about' respectively, but in this case they do not. 

## Solution

The `bugSolution.js` file shows the solution. In this case, the issue was that the link behavior was not correctly configured within the app directory structure.  The solution demonstrates a proper way to manage links to ensure navigation functions as intended.