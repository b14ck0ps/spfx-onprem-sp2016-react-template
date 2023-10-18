# SharePoint Framework (SPFx) Project Setup
_Author: Azran_

_Framework: SharePoint Framework (SPFx) 1.6.0 X React_

_Server: SharePoint 2016 On-Premises_


This guide will help you set up and run SharePoint Framework (SPFx) projects using the following dependencies:

- `@microsoft/generator-sharepoint@1.6.0`
- `gulp-cli@2.3.0`
- `npm@6.13.4`
- `yo@2.0.0`

## Prerequisites

Before getting started, ensure you have the following installed on your system:

- Node.js (Version 8.17.0)
- npm (Version 6.13.4)

## Disable HTTP/2 for Node.js 8.17.0

If you are working with Node.js version 8.17.0 and need to disable HTTP/2, you can set the `NODE_NO_HTTP2` environment variable. To do this, run the following command:
```bash
export NODE_NO_HTTP2=1
```
## Project Setup

1. Install Yeoman (yo) and SharePoint generator:

```bash
npm install -g yo @microsoft/generator-sharepoint@1.6.0
```

2. Create a new SPFx project:

```bash
yo @microsoft/sharepoint
```

3. Follow the prompts to configure your SPFx project.

4. Install Gulp CLI:

```bash
npm install -g gulp-cli@2.3.0
```

5. Run the development server:

```bash
gulp serve
```

This will start the development server for your SPFx project.

## Additional Information

- Make sure to customize the project settings and configurations based on your project requirements.
- Refer to the official SharePoint Framework documentation for more details: [SPFx Documentation](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/sharepoint-framework-overview)