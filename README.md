# Forge "Traffic Light custom field"

This project contains a Forge app that adds a Jira custom field type representing a traffic light status. The field is a single-select list with the predefined values:

- "⚪️⚪️⚪️" (default)
- "🔴⚪️⚪️"
- "⚪️🟡⚪️"
- "⚪️⚪️🟢"

## Requirements

See [Set up Forge](https://developer.atlassian.com/platform/forge/set-up-forge/) for instructions to get set up.

## Quick start

- Install dependencies in the root directory:

```sh
npm install
```

- Install dependencies for the custom field UI:

```sh
cd static/edit
npm install
```

- Build the UI (from the `static/edit` directory):

```sh
npm run build
```

- Build and deploy the app:

```sh
forge deploy
```

- Install the app on an Atlassian site:

```sh
forge install
```

- Develop your app locally by running:

```sh
forge tunnel
```

### Notes

- Use `forge deploy` to persist code changes.
- Use `forge install` to install the app on a new site.
- Once the app is installed on a site, deployments automatically update the app without reinstalling.

## Support

See [Get help](https://developer.atlassian.com/platform/forge/get-help/) for how to get help and provide feedback.
