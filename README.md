[//]: # "This README.md file is auto-generated, all changes to this file will be lost."
[//]: # "To regenerate it, use `npm run generate-scaffolding`."
<img src="https://avatars2.githubusercontent.com/u/2810941?v=3&s=96" alt="Google Cloud Platform logo" title="Google Cloud Platform" align="right" height="96" width="96"/>

# [Cloud AutoML: Node.js Client](https://github.com/GoogleCloudPlatform/google-cloud-node)

[![release level](https://img.shields.io/badge/release%20level-alpha-orange.svg?style&#x3D;flat)](https://cloud.google.com/terms/launch-stages)
[![npm version](https://img.shields.io/npm/v/@google-cloud/automl.svg)](https://www.npmjs.org/package/@google-cloud/automl)
[![codecov](https://img.shields.io/codecov/c/github/GoogleCloudPlatform/google-cloud-node/master.svg?style=flat)](https://codecov.io/gh/GoogleCloudPlatform/google-cloud-node)

> Node.js idiomatic client for [AutoML][product-docs].

Train high quality custom machine learning models with minimum effort and machine learning expertise


* [AutoML Node.js Client API Reference][client-docs]
* [github.com/GoogleCloudPlatform/google-cloud-node](https://github.com/GoogleCloudPlatform/google-cloud-node)
* [AutoML Documentation][product-docs]

Read more about the client libraries for Cloud APIs, including the older
Google APIs Client Libraries, in [Client Libraries Explained][explained].

[explained]: https://cloud.google.com/apis/docs/client-libraries-explained

**Table of contents:**

* [Quickstart](#quickstart)
  * [Before you begin](#before-you-begin)
  * [Installing the client library](#installing-the-client-library)
  * [Using the client library](#using-the-client-library)
* [Versioning](#versioning)
* [Contributing](#contributing)
* [License](#license)

## Quickstart

### Before you begin

1.  Select or create a Cloud Platform project.

    [Go to the projects page][projects]

1.  Enable billing for your project.

    [Enable billing][billing]

1.  Enable the Cloud AutoML API.

    [Enable the API][enable_api]

1.  [Set up authentication with a service account][auth] so you can access the
    API from your local workstation.

[projects]: https://console.cloud.google.com/project
[billing]: https://support.google.com/cloud/answer/6293499#enable-billing
[enable_api]: https://console.cloud.google.com/flows/enableapi?apiid=automl
[auth]: https://cloud.google.com/docs/authentication/getting-started

### Installing the client library

    npm install --save @google-cloud/automl

### Using the client library

```javascript
// Import the Google Cloud client library
const automl = require('@google-cloud/automl');

// Creates a client
const client = new automl.AutoMlClient();

```


The [AutoML Node.js Client API Reference][client-docs] documentation
also contains samples.

## Versioning

This library follows [Semantic Versioning](http://semver.org/).

This library is considered to be in **alpha**. This means it is still a
work-in-progress and under active development. Any release is subject to
backwards-incompatible changes at any time.

More Information: [Google Cloud Platform Launch Stages][launch_stages]

[launch_stages]: https://cloud.google.com/terms/launch-stages

## Contributing

Contributions welcome! See the [Contributing Guide](https://github.com/GoogleCloudPlatform/google-cloud-node/blob/master/.github/CONTRIBUTING.md).

## License

Apache Version 2.0

See [LICENSE](https://github.com/GoogleCloudPlatform/google-cloud-node/blob/master/LICENSE)

[client-docs]: https://cloud.google.com/nodejs/docs/reference/automl/latest/
[product-docs]: https://cloud.google.com/automl/docs/
[shell_img]: https://gstatic.com/cloudssh/images/open-btn.png

