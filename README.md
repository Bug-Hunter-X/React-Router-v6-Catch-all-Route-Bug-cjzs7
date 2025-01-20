# React Router v6 Catch-all Route Issue

This repository demonstrates a common issue in React Router v6 where the catch-all route (`/*`) interferes with other, more specific routes.  The issue occurs when the catch-all route is placed after more specific routes.

**Problem:** The catch-all route will always match, overriding any other route definitions.

**Solution:** Rearrange route order to define the catch-all route *before* any other routes.