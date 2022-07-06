# GCP Python/Flask OpenTelemetry sample

A simple demonstration of a Flask application with OpenTelemetry tracing.

## Quickstart

You need to have glcoud installed and configured to use this and view traces in Cloud Tracing.
Ensure you are logged in to Google Cloud Platform and set to the correct project.

```
source ./bin/configure
flask run
```

To run entirely locally, simply set the Flask environment to `development` like this:
```sh
export FLASK_ENV=development
```
