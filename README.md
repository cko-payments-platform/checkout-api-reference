# Checkout.com API Reference

[![Build Status](https://vercel.com/cko-docs/checkout-api-reference)](https://vercel.com/cko-docs/checkout-api-reference)

---

## NOTE

Review from the documentation team is now mandatory. You won't be able to merge changes until we have reviewed. Use the list below to see which Technical Writer is a assigned to you. We will approve on the same day. Contact [@Chrisi Webster](https://github.com/chrisi-webster-cko) if your assigned Technical Writer is away or unable to help.

### [@Ben Ahmady](https://github.com/ben-ahmady-cko)

- Payments
- Payouts (including FX)
- Notifications
- Vault

### [@Chrisi Webster](https://github.com/chrisi-webster-cko)

- Marketplaces
- Payment interfaces
- General updates

### [@Cristina Szilagyi](https://github.com/cristina-szilagyi-cko)

- APMs
- 3DS Authentication
- Issuing

### [@Neal Goldsmith](https://github.com/neal-goldsmith-cko)

- Prism (risk)
- Disputes
- Reporting

---

## Links

- Documentation: https://api-reference.checkout.com
- SwaggerUI: https://api-reference.checkout.com/swagger-ui/
- Look full spec:
  - JSON https://api-reference.checkout.com/swagger.json
  - YAML https://api-reference.checkout.com/swagger.yaml
- Preview spec version for branch `[branch]`: Will be attached to a PR by Vercel Bot. These are autogenerated and can be found in CKO-Docs Vercel Project
- On preview branchs, add '/preview/crusoe/ to view the NAS version of the Spec.

**NOTE:** All above links are updated only after Vercel build finishes

## Working on specification

### Install

1. Install [Node JS](https://nodejs.org/)
2. Install [dotnet cli](https://dotnet.microsoft.com/download)
3. Clone repo and inside the repo directory
   - Run `npm install`

### Usage

1. Run `npm run start`
2. Check console output to see where local server is started
3. Make changes using your favorite editor (or the `swagger-editor` shipped with the project - look for the URL in the console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change  
   **TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm run test`

### Contribute

1. Your contribution should have a JIRA ticket on the [Documentation Board](https://checkout.atlassian.net/secure/RapidBoard.jspa?rapidView=543&projectKey=DOC)
2. Name your branch `<type>/<JIRA-issue-key>-<JIRA-issue-title>`  
   _for example: "task/DOCS-534-add-oas3-operationid"_
3. Work, commit, push
4. Have a break, drink some coffee
5. Repeat (3) through (4) until finished
6. Create a PR and request review from
   - a peer developer (if necessary)
   - [@Ben Ahmady](https://github.com/ben-ahmady-cko), [@Jack Hutchinson](https://github.com/jack-hutchinson-cko), [@Chrisi Webster](https://github.com/chrisi-webster-cko), [@Cristina Szilagyi](https://github.com/cristina-szilagyi-cko), or [@Neal Goldsmith](https://github.com/neal-goldsmith-cko)
7. After merging the PR, please check if your branch can be deleted

### Troubleshooting

- Verify if Node.js is installed `node --version`, using v14
- Verify if Gulp is installed `gulp --version`, using v4.0.2
- Verify if dotnet is installed `dotnet --version`, using v5.0.102
