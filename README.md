# Sync Platform For Agency

Github Action for triggering the platform sync workflow in FE Platform repository for a given brand.


## Arguments

| Argument Name            | Required   | Default     | Description           |
| ---------------------    | ---------- | ----------- | --------------------- |
| `repo_token`             | True       | N/A         | Github access token of the platform repository owner. |
| `brand_name`             | True       | N/A         | The name of the brand that needs to be synced with platform |


## Example Usage

```yaml
- uses: robinvarshn/platform-sync@master
  with:
    repo_token: ${{ secrets.REPO_TOKEN }}
    brand_name: <agency_brand_name>
```

