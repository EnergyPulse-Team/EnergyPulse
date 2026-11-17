# EnergyPulse

## Smart Energy Consumption Analytics Platform

EnergyPulse is a smart platform designed to monitor, analyze, and
visualize energy consumption data, helping users understand usage
patterns and make data-driven decisions.

## Project Goals

- Monitor energy consumption.
- Analyze energy usage patterns.
- Present meaningful analytics and insights.
- Support better energy management and efficiency.
- Provide a clear and accessible user experience.

## Technology

The project is developed using a Full-Stack architecture.

- Frontend: React
- Backend: Node.js
- Database: MongoDB
- Version Control: Git and GitHub
- DevOps: Docker, CI/CD, and Cloud Deployment (project phases)

## Repository Structure

```text
EnergyPulse/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── CODEOWNERS
│   └── PULL_REQUEST_TEMPLATE.md
├── README.md
├── .gitignore
├── .editorconfig
└── LICENSE
```

## Branching Strategy

| Branch | Purpose |
|---|---|
| main | Stable production-ready code |
| develop | Integration and development |
| feature/* | New features and team tasks |
| bugfix/* | Bug fixes |
| hotfix/* | Urgent production fixes |

### Contribution Workflow

1. Create a feature branch from develop.
2. Implement your changes.
3. Test your changes locally.
4. Push your branch to GitHub.
5. Open a Pull Request targeting develop.
6. Request the required code reviews.
7. Merge after approval and successful checks.

## Code Ownership

The Data Analysis team reviews changes related to:

- `/data/`
- `/analytics/`

See `.github/CODEOWNERS` for ownership rules.

## Development Guidelines

- Follow the existing project conventions.
- Use meaningful branch and commit names.
- Keep Pull Requests focused and documented.
- Test changes before submitting a Pull Request.
- Update documentation when necessary.

## Security Guidelines

- Never commit passwords, API keys, tokens, or credentials.
- Store sensitive configuration in environment variables.
- Use GitHub Secrets for CI/CD credentials.
- Never upload `.env` files containing real secrets.
- Report security vulnerabilities privately to the repository maintainers.

## License

See the [LICENSE](LICENSE) file.
