# Go Version Update Test

This project tests Renovate's ability to automatically update the Go version specified in go.mod files.

## Purpose

The repository serves as a testbed to verify if Renovate can detect and propose updates from Go 1.22 to the latest available version.

## Configuration

The project includes:

- GitHub Actions workflow for CI/CD
- Renovate configuration optimized for Go updates
- Automated testing and validation

## Setup

1. Clone the repository
2. Ensure Renovate is configured for your repository
3. Wait for Renovate to detect the Go version update

## How It Works

The project uses:

- go.mod specifying Go 1.22
- Renovate configuration with Go-specific settings
- GitHub Actions workflow to validate updates

## Repository Structure

```
.
├── .github/workflows/ci.yml
├── .renovaterc.json
├── go.mod
└── README.md
```

## Status

Monitor the Dependency Dashboard in your repository's issues section to track Renovate's update proposals.

## Requirements

- GitHub repository
- Renovate Bot access
- Go 1.22 or higher

