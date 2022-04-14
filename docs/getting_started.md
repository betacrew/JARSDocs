---
layout: default
title: Getting Started
nav_order: 2
---

## Let's Begin!

To generate the JARS project, run the following command
{: .fs-6 .fw-300 }

```bash
npx generate-jars-app app-name
```

Change the port to your preference by...
{: .fs-6 .fw-300 }
// TODO: Need to add docs to help users change ports

Then use the following to run the web project,
```bash
cd app-name
npm run start-web
```

Go to the link printed in the console. You will now see the JARS welcome screen.
{: .fs-6 .fw-300 }

JARS uses Expo under the hood to enable native development. Run the following to start the expo project:
{: .fs-6 .fw-300 }
```bash
cd app-name
npm run start-expo
```

<br/>

[Let's talk about the JARS project structure](project_structure.html){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
