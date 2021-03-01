# Alertify.js WebJar (alertify.js)

[Alertify.js](https://github.com/alertifyjs/alertify.js) is an customizable JavaScript notification system.. This [WebJar](https://webjars.org) includes the corresponding JavaScript and CSS files. Alertify.js is licensed under the [MIT License](http://www.opensource.org/licenses/MIT).

WebJars are usually built using a plain Maven POM. This WebJar uses the
[Apache Maven AntRun Plugin](https://maven.apache.org/plugins/maven-antrun-plugin/) to download the Alertify.js files from
GitHub and puts them into the Java archive.

## Usage

Just include this WebJar into your project. For Maven, you can use the following snippet:

```xml
<dependency>
    <groupId>org.webjars</groupId>
    <artifactId>alertify.js</artifactId>
    <version>1.0.11</version>
</dependency>
```

And here is a Gradle snippet for you:

```groovy
implementation 'org.webjars:alertify.js:1.0.11'
```

## Building

Just call

    mvn clean install

and the Jar is built. You can check the output in the target folder. Please make sure that all
required files are included and have proper content.

## Contributing

I highly welcome your updates and improvements. Please open a pull request if you want to contribute
to the Alertify.js WebJar. Thanks in advance!
