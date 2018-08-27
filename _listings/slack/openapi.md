swagger: "2.0"
x-collection-name: Slack
x-complete: 1
info:
  title: Slack
  description: one-way-to-interact-with-the-slack-platform-is-its-http-rpcbased-web-api-a-collection-of-methods-requiring-oauth-2-0based-user-bot-or-workspace-tokens-blessed-with-related-oauth-scopes-
  version: 1.0.3
host: slack.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /team.billableInfo:
    get:
      summary: Get Billable Info
      description: Gets billable users information for the current team.
      operationId: team_billableInfo
      x-api-path-slug: team-billableinfo-get
      parameters:
      - in: query
        name: token
        description: Authentication token
      - in: query
        name: user
        description: A user to retrieve the billable information for
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Billing