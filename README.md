# disQo.ai Documentation

Welcome to the disQo.ai documentation repository. disQo.ai is an AI-powered, agentic workflow automation platform that enables users to augment their work by creating AI-powered workflows and agents tailored to various roles within the Software Development Life Cycle (SDLC).

## About disQo.ai

disQo.ai empowers professionals across the SDLC with specialised AI agents. Here are some examples of our current and upcoming features:

- **Business Analysts** can leverage Requirement Analyser agents
- **Quality Assurance** professionals can utilise Test Case Generator agents
- **Developers** can access code review and optimisation agents
- **Project Managers** can benefit from project planning and tracking agents

These agents represent just a sample of our capabilities. We have more specialised agents and features in our roadmap that will further enhance productivity and efficiency across your development workflow. Stay tuned for exciting updates!

## Documentation Structure

This documentation covers:

- **Agents**: AI-powered assistants for specific roles and tasks
- **Workflows**: Automated process orchestration
- **Knowledge Base**: Centralised information management
- **Integrations**: Third-party system connections
- **Analytics**: Performance insights and metrics
- **Activities**: Audit trail and activity monitoring

## Development

To contribute to or preview the documentation locally:

1. Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):
   ```bash
   npm i -g mintlify
   ```

2. Run the development server at the root of this documentation (where `docs.json` is):
   ```bash
   mintlify dev
   ```

## Publishing Changes

Changes are automatically deployed to production when pushed to the default branch. The GitHub App handles deployment automatically.

## Quick Links

- [disQo.ai Platform](https://app.disqoai.com)
- [Main Website](https://disqoai.com)
- [Contact Support](https://tiqtoq-uk.atlassian.net/servicedesk/customer/portal/4)

## Troubleshooting

- **Mintlify dev isn't running**: Run `mintlify install` to re-install dependencies
- **Page loads as a 404**: Ensure you're running the command in a folder containing `docs.json`
