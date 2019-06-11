# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2016-09-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-serviceDiagnosticsSettings_API/2016-09-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:04+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets the active diagnostic settings for the specified resource. **WARNING**: This method will be deprecated in future releases.

*Tags:* `ServiceDiagnosticSettings`

#### Input Parameters
* `resourceUri` - _required_ - The identifier of the resource.
* `api-version` - _required_ - Client Api Version.

### Updates an existing ServiceDiagnosticSettingsResource. To update other fields use the CreateOrUpdate method. **WARNING**: This method will be deprecated in future releases.

#### Input Parameters
* `resourceUri` - _required_ - The identifier of the resource.
* `api-version` - _required_ - Client Api Version.

### Create or update new diagnostic settings for the specified resource. **WARNING**: This method will be deprecated in future releases.

*Tags:* `ServiceDiagnosticSettings`

#### Input Parameters
* `resourceUri` - _required_ - The identifier of the resource.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-service-diagnostics-settings-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
