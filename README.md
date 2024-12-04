# Next.js Runtime Error

This repository demonstrates a common runtime error in Next.js applications.  The error occurs when a page attempts to access a variable that has not been defined.

## Problem

The `pages/about.js` file attempts to use the variable `nonExistentVariable` which is not defined anywhere within the component.  This results in a runtime error when the page is loaded.

## Solution

The solution involves identifying and fixing the source of the undefined variable.  In this case, either define the `nonExistentVariable` or remove the reference to it.  The corrected code is provided in `aboutSolution.js`

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the Next.js development server.
4. Navigate to `/about` in your browser. You will see the runtime error.
5. Replace `pages/about.js` with `pages/aboutSolution.js` and refresh the browser.