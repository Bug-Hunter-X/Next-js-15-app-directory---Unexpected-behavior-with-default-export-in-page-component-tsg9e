# Next.js 15 app directory - Unexpected behavior with default export in page component

This repository demonstrates an unexpected behavior encountered when using a default export in a page component within the Next.js 15 app directory.  The issue involves the rendering of the component and potential conflicts with other aspects of the app directory structure.

## Bug Description

When using a simple default export in a page component (e.g., `pages/index.js`), Next.js 15 might exhibit unexpected behavior.  This might manifest as rendering issues, unexpected routing, or other inconsistencies,  depending on how other aspects of your application are structured.

## How to reproduce

1. Clone this repository.
2. Navigate to the `bug` directory.
3. Run `npm install`.
4. Run `npm run dev`.
5. Observe the behavior.  The page might not render correctly or as expected.

## Solution

The solution involves migrating the export style to use a named export.