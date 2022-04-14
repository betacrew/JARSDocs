---
layout: default
title: Getting Started
nav_order: 2
---

## Let's Begin!
- To generate the JARS project, run the following command

```bash
npx generate-jars-app app-name
```

Change the port to your preference by...

// TODO: Need to add docs to help users change ports

Then use the following to run the web project,
```bash
cd app-name
npm run start-web
```

Go to the link printed in the console. You will now see the JARS welcome screen.

JARS uses Expo under the hood to enable native development. Run the following to start the expo project:
```bash
cd app-name
npm run start-expo
```

<br/>

[Let's talk about the JARS project structure](project_structure.html){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
