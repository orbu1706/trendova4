v12 Netlify routing fix: the Netlify Function now imports the actual shared API core module.
The previous v10 function referenced a missing api/[...path].js module, which caused requests to fail.
