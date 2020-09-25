# kissmetrics

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![AppVersion: 1.0](https://img.shields.io/badge/AppVersion-1.0-informational?style=flat-square)

A Helm chart for Kubernetes

**Homepage:** <https://github.com/tidepool-org/development/charts>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| secret.data_.APIKey | string | `""` | plaintext Kissmetrics API Key |
| secret.data_.Token | string | `""` | plaintext Kissmetrics Token |
| secret.data_.UCSFAPIKey | string | `""` | plaintext UCSF Kissmetrics Token |
| secret.data_.UCSFWhitelist | string | `""` | plaintext UCSF metrics whitelist |
| secret.enabled | bool | `false` | Whether to use create kissmetrics secret |