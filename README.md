# Forge Issue Countries

[![Atlassian license](https://img.shields.io/badge/license-Apache%202.0-blue.svg?style=flat-square)](LICENSE)

This is an example [Forge](https://developer.atlassian.com/platform/forge/) app that displays an issue panel comprising a world map highlighting the countries identified by a custom field.

## Usage

When viewing an issues, a map will appear below the description of the issue. Use the countries custom field to select the countries that the issue applied to. After changing the countries, click the "Refresh" button below the map to hgihlight the selected countries.

![Animation of translate issue content panel](./demo.gif)

## Installation

1. Follow the instructions on [Example Apps](https://developer.atlassian.com/platform/forge/example-apps/) to copy, deploy, and install this Forge app.
1. Navigate to a Jira issue page. You should see the a panel below the description titled "Countries" which contains a world map. This panel is produced by the app.
1. At the bottom of the panel, you should see a button labelled "Create country field". Click the button to create the custome field required by the app.
1. Reload the issue view and you should see the "Create country field" button is no longer visible.
1. To the right of the issue view, check if you see a field labelled "Countries". If you don't, visit the [custom fields admin](https://your-tenant.atlassian.net/secure/admin/ViewCustomFields.jspa), click the "..." button beside the "Countries" field, select "Associate to screens" and then select the screens corresponding to your issue view being shown.
1. Reload the issue view and check the "Countries" field is visible.
1. Select one of more countries from the "Countries" field.
1. Click the "Refresh" button below the countries map and check the selected countries are highlighted.

## Debugging

You can use the [`forge tunnel`](https://developer.atlassian.com/platform/forge/change-the-frontend-with-forge-ui/#set-up-tunneling) command to run your Forge app locally. 

## License

Copyright (c) 2020 Atlassian and others.
Apache 2.0 licensed, see [LICENSE](LICENSE) file.

[![From Atlassian](https://raw.githubusercontent.com/atlassian-internal/oss-assets/master/banner-cheers.png)](https://www.atlassian.com)
