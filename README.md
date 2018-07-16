# aws-s3-js
aws s3 client for javascript

Built with browserify as explained [here](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/building-sdk-for-browsers.html#building-using-browserify)


~~~bash
$ AWS_SERVICES=s3 browserify index.js > browser-app.js
~~~

where index.js is:
~~~javascript
var AWS = require('aws-sdk');
~~~

