# Akto code analysis action

## Example usage

```yaml
- name: Akto code analysis
  uses: akto-api-security/code-analysis-action@v1
  with:
    AKTO_DASHBOARD_URL: "<AKTO_DASHBOARD_URL>"
    AKTO_API_KEY: ${{ secrets.AKTO_API_KEY }}
    API_COLLECTION_NAME: juice_shop_demo
```