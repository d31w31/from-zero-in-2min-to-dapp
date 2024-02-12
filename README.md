# From zero in 2 minutes to dAPP

*Do you like a visual overview?*

-> [From zero in 2 min to dApp Visual Overview](https://www.figma.com/file/jKyVjm7MUBuMQSEMMJXjcJ/From-zero-in-2-min-to-dApp?node-id=1%3A2645)

## (0) Prerequisites

1. 2 min time
2. An existing and authenticated GitHub account
3. Some HTML to deploy as dApp

## Workflow

### (1) Create Internet Identity & Juno Satellite

#### Navigate to Juno

1. Go to https://juno.build/
2. Click "Start building" *(have a look at the top right of the page)*

#### Create Internet Identity

1. Click "Continue with Internet Identity" to sign up with Internet Identity
2. Click "Create Internet Identity"
3. Click "Continue without Passkey"
4. Click "Continue and set pin" *(and write it down at a secure place)*
5. Prove you are not a robot and click "Next"
6. Copy your Internet Identity *(number)* and store it in a save place
7. Click "I saved it, continue"

#### Create your dApp carrying Satellite

1. At https://console.juno.build/ click "Launch a new Satellite"
2. Enter a name "Cool just 2min until Web3 🚀" & click "Create satellite" & click "Continue"
3. Go to "Satellite > Overview" *(should be be visible by default)*
4. Move from "Satellite > Overview" to "Satellite > Controller"
5. Click "Add a Controller"
6. Select "Generate a new controller" in the opened modal
7. Ensure scope is set to "Read-Write"
8. Click "Submit"
9. Copy and paste the "Satellite" ID *(e.g. `apwq6-eaaaa-aaaal-adsza-cai` <- don't use this one this is mine)*
10. Copy and paste the "Secret token ⚠️" to a secure location
11. Click "Close"

### (2) Setup GitHub

1. Sign into
2. Move to GitHub https://github.com/dennyweiss/from-zero-in-2min-to-dapp
3. Click "Fork" repository, don't touch the defaults & click "Create fork"
4. Go to "⚙️Settings > Secrets and variables > Actions"
5. Select the "Secrets" tab and click "New repository secret"
6. Add "JUNO_TOKEN" as name and the formerly stored "Secret token ⚠️" as value and click "Add secret"
7. Select the "Variables" tab and click "New repository variable"
8. Add "JUNO_SATELLITE_ID" as name and the formerly stored "Satellite" ID as value and click "Add variable"
9. Go to "Actions" and click "I understand my workflows, go ahead and enable them"
10. Move to Code & open `public` directory
11. Use dropdown "Add file" and change it to "Upload files"
12. Drag the files from "Prerequisites step 3" into the "Drag files here to add them to your repository" file drop area
13. Click "Commit changes"

### (3) Be proud about your dApp

Go to `https://ADD_YOUR_SATELLITE_ID_HERE.icp0.io` to inspect the newly deployed dApp

## *Project rationale & Acknowledgments*

The **"From Zero in 2 Minutes to dApp"** showcase was developed as inspiration and submitted to the ["From Zero to dApp" Hackathon 2024](https://www.encode.club/zero-to-dapp-hackathon) hosted by [Encode Club](https://www.encode.club/). 

It aims to empower non-developers by enabling the swift creation of websites on the Web3 platform in approximately two minutes. This project was made possible through the utilization of the [Internet Computer](https://internetcomputer.org/) and was significantly inspired by the contributions of [David Dal Busco](https://www.linkedin.com/in/david-dal-busco/). Specifically, his pioneering work on **[Juno](https://juno.build/)**, an open-source blockchain platform, allows developers and non-developers alike to build Web3 apps with the ease reminiscent of Web2 development practices.
For the practical execution of this project, I leveraged two GitHub repositories provided by David Dal Busco: the [Juno Action](https://github.com/junobuild/juno-action) GitHub Action for deploying websites to Juno and the [Juno Examples
](https://github.com/junobuild/examples) repository containing website starter kits. These resources were instrumental in developing the showcase project as the foundational resource for its creation.

Furthermore, I'd like to acknowledge [Lukas Vozda](https://twitter.com/lukasvozda) for his asynchronous yet serendipitously similar proposal to expand [Juno](https://juno.build/) and [ICP's](https://internetcomputer.org/) reach among non-developers. Although Lukas and I worked independently, his idea resonates with the essence of this showcase, highlighting the collective drive within our community to make Web3 more accessible to a broader audience.

While bringing ["From Zero in 2 Minutes to dApp"](https://github.com/dennyweiss/from-zero-in-2min-to-dapp) to live was an individual endeavor, it stands on the shoulders of remarkable contributions from the [Internet Computer](https://internetcomputer.org/), [David Dal Busco](https://www.linkedin.com/in/david-dal-busco/), and the inspiring ideas shared by [Lukas Vozda](https://twitter.com/lukasvozda). 🙏🏽

### Resources

1. [Juno](https://juno.build/)
2. [Juno Docs > Creating the GitHub Action](https://juno.build/docs/miscellaneous/github_actions#creating-the-github-action)
3. [Juno Examples – Vanilla - TypeScript + Vite](https://github.com/junobuild/examples/tree/main/vanilla/vite-typescript)
4. [Internet Computer Docs](https://internetcomputer.org/docs/current/home)
