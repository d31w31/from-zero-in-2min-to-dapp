# From zero in 2 minutes to dAPP

## Prerequisites

1. 2 min time
2. An existing and authenticated GitHub account
3. Some HTML to deploy as dApp

## Workflow

1. Go to https://juno.build/
2. Click "Start building" *(have a look at the top right of the page)*
3. Sign up with Internet Identity <!-- @warn be verified -->
4. At https://console.juno.build/ click "Launch a new Satellite"
5. Enter a name "Cool just 2min until Web3 🚀"
6. Click "Create satellite"
7. Go to "Satellite > Overview" *(should be be visible by default)*
8. Move from "Satellite > Overview" to "Satellite > Controller"
9. Click "Add a Controller"
10. Select "Generate a new controller" in the opened modal
11. Ensure scope is set to "Read-Write"
12. Click "Submit"
13. Copy and paste the "Satellite" ID *(e.g. `apwq6-eaaaa-aaaal-adsza-cai` <- don't use this one this is mine)*
14. Copy and paste the "Secret token ⚠️" to a secure location
15. Click "Close"
16. Move to GitHub https://github.com/dennyweiss/from-zero-in-2min-to-dapp
17. Click fork repository
18. Go to "⚙️Settings > Environments" and click "New environment"
19. Enter the name "production" and click "Configure environment"
20. Don't touch the default and click "Save protection rules"
21. Click "Environment secrets > Add secret"
22. Add "JUNO_TOKEN" as name and the formerly stored "Secret token ⚠️" as value and click "Add secret"
23. Click "Environment variables > Add variable"
24. Add "JUNO_SATELLITE_ID" as name and the formerly stored "Satellite" ID as value and click "Add variable"
25. Move to Code
26. Use dropdown "Add file" and change it to "Upload files"
27. Drag the HTML files from "Prerequisites step 3" here
28. Press commit changes




