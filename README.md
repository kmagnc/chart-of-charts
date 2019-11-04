# chart-of-charts
The following repo is a proof of concept Helm Chart orchestrating multiple deployments of one basic helm chart in varying configurations.

### A/C:
Deploy multiple instances of the same helm chart with different configurations

###Layout:

chart-of-charts (this parent repo)
- basic-chart-original  (the same basic nginx repo, port #81)
- basic-chart-location0 (the same basic nginx repo, port #82)
- basic-chart-location1 (the same basic nginx repo, port #83)

### How to use:
`helm install . --name kmagrules`
