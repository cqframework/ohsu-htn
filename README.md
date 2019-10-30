# ohsu-htn
Oregon Health & Science University Hypertension Management Implementation Guide
Release 1 (v0.1.0) for FHIR R4 (4.0.0)

This project provides the source for the Oregon Health & Science University Hypertension Management Implementation Guide.

Commits to this repository will automatically trigger a new build of the IG, which will then be published to the following location:

[http://build.fhir.org/ig/cqframework/ohsu-htn/](http://build.fhir.org/ig/cqframework/ohsu-htn/)

Build log is available here:

[http://build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/cqframework/ohsu-htn](http://build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/cqframework/ohsu-htn)

Debugging information is available here:

[http://build.fhir.org/ig/HL7/cqf-recommendations/debug.tgz](http://build.fhir.org/ig/cqframework/ohsu-htn)

## Local Build

In Windows environments, the `_updatePublisher.bat` file can be used to download a local copy of the latest IG publisher:

```
_updatePublisher
```

If the above command doesn't work, the latest version of the IG publisher is available here:

[https://fhir.github.io/latest-ig-publisher/org.hl7.fhir.publisher.jar](https://fhir.github.io/latest-ig-publisher/org.hl7.fhir.publisher.jar)


And the `publish.bat` file can be used to publish the ig:

```
publish
```

