<h2 align="center">
I'm a Software Development Engineer in Test and this is a Demo project of Cypress Integration with browserstack
</h2> 
<h6 align="center">
Do a `npm install` first then install browserstack `npm install -g browserstack-cypress-cli`
</h6>
<h6 align="center">
And follow the following steps:
</h6>
<p align="left">

1. `browserstack-cypress init` : run the command

2. Put this into the browserstack.json file:

```
{
  "auth": {
    "username": "<Your Username>",
    "access_key": "<Your Access_Key>"
  },
  "browsers": [
    {
      "browser": "chrome",
      "os": "Windows 10",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "firefox",
      "os": "Windows 10",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "edge",
      "os": "Windows 10",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "chrome",
      "os": "OS X Mojave",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "firefox",
      "os": "OS X Mojave",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "edge",
      "os": "OS X Mojave",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "chrome",
      "os": "OS X Catalina",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "firefox",
      "os": "OS X Catalina",
      "versions": ["latest", "latest-1"]
    },
    {
      "browser": "edge",
      "os": "OS X Catalina",
      "versions": ["latest", "latest-1"]
    }
  ],
  "run_settings": {
    "cypress_config_file": "cypress.json",
    "cypress_version": "9.7.0",
    "project_name": "My Cypress Project",
    "build_name": "build-1",
    "exclude": [],
    "parallels": "2",
    "npm_dependencies": {},
    "package_config_options": {},
    "headless": true
  },
  "connection_settings": {
    "local": false,
    "local_identifier": null,
    "local_mode": null,
    "local_config_file": null
  },
  "disable_usage_reporting": false
}

```

3. `browserstack-cypress run --sync`: run the command to start browserstack
</p>
