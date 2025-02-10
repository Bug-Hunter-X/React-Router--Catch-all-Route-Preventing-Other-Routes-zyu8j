# React Router Catch-all Route Issue

This repository demonstrates a common issue in React Router where a catch-all route (`path="/*"`) is placed before other routes, preventing them from rendering correctly.  The solution shows how to fix this by placing the catch-all route as the last route defined.  This ensures other routes are correctly matched first.

## Problem

When a catch-all route (`path="/*"`) is placed before other more specific routes in `Routes`, it will always match, effectively preventing any other route from being used, resulting in the catch-all route always being displayed.