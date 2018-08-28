# ember-cli-deprecation-workflow-plus

**NOTE**
This is a forked version of [`ember-cli-deprecation-workflow`](https://github.com/mixonic/ember-cli-deprecation-workflow) with additional functionality.

Please review the original addon's README for installation and usage instructions.

This package adds the ability to customize the config directory used.

## Customization

In your app's `ember-cli-build`, add an entry under options for this addon:

```javascript
const options = {
  'ember-cli-deprecation-workflow-plus': {
    configDir: '/my-config'
  }
}
```
