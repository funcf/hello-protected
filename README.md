# hello-protected

A simple example app that runs on Cloud Foundry serving a protected JSON file using the Staticfile Buildpack.

**Usage:** `cf push protected`

Once the app is running, simply GET the /data.json content.

**User:** `Hello`
**Password:** `World!`

[More Details about the Staticfile Buildpack](https://docs.cloudfoundry.org/buildpacks/staticfile/#staticfile)

**Please Note: This is an example app with a unsecure password that you would not have in git without gitcrypt for productive use cases.**
