# ConnecSys Micronaut App Template built on the Micronaut framework

ConnecSys app template is built on the Micronaut framework. Configured to run on the Google App Engine Java 17 standard
environment. With option to build GraalVM native image that can be deployed using Cloud Build.

It enables developers to create scalable and efficient web applications that run on App Engine.

## Micronaut 4.0.1 Documentation

- [User Guide](https://docs.micronaut.io/4.0.1/guide/index.html)
- [API Reference](https://docs.micronaut.io/4.0.1/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/4.0.1/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/latest/index.html)
- [Using the App Engine Maven Plugin](https://cloud.google.com/appengine/docs/standard/java-gen2/using-maven)

---

## App Template prerequisites

* Java 17 (temurin-17)
* Maven installed, check with `mvn -v`
* gcloud CLI app-engine-java component: `gcloud components install app-engine-java`
* Check the target GCP project: `gcloud config list`
    * Optionally set the target GCP project: `gcloud config set project [PROJECT_ID]`

## Building locally and Deploying by Maven plugin

```
mvn package appengine:deploy
```
