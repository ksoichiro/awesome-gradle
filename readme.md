# Awesome Gradle

> A curated list of awesome Gradle plugins and resources for a better development workflow automation.

Inspired by the [awesome](https://github.com/sindresorhus/awesome), [awesome-gulp](https://github.com/alferov/awesome-gulp) and some other awesome lists.

## Table of contents

- [Plugins](#plugins)
  - [Language](#language)
  - [Code quality](#code-quality)
  - [Code generation](#code-generation)
  - [Java application development](#java-application-development)
  - [Web application development](#web-application-development)
  - [Android application development](#android-application-development)
  - [iOS and Mac application development](#ios-and-mac-application-development)
  - [Editor and IDE integration](#editor-and-ide-integration)
  - [Templating](#templating)
  - [Database](#database)
  - [Dependency management](#dependency-management)
  - [Debugging](#debugging)
  - [Testing](#testing)
  - [Building](#building)
  - [Packaging](#packaging)
  - [Releasing](#releasing)
  - [Notification](#notification)
  - [Cloud services](#cloud-services)
  - [SCM](#scm)
  - [CI](#ci)
  - [VM and container](#vm-and-container)
- [Boilerplates](#boilerplates)
- [Resources](#resources)
  - [General Resources](#general-resources)
  - [Official Documentation](#official-documentation)

## Plugins

> Notice: in the following descriptions, "Official plugin" means that it's provided as a builtin plugin by Gradle.

### Language

- [java](https://docs.gradle.org/current/userguide/java_plugin.html) - Official plugin that adds Java compilation, testing and bundling capabilities.
- [groovy](https://docs.gradle.org/current/userguide/groovy_plugin.html) - Official plugin that adds support for building Groovy projects.
- [scala](https://docs.gradle.org/current/userguide/scala_plugin.html) - Official plugin that adds support for building Scala projects.
- [antlr](https://docs.gradle.org/current/userguide/antlr_plugin.html) - Official plugin that adds support for generating parsers using [Antlr](http://www.antlr.org/).
- [assembler](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds native assembly language capabilities to a project.
- [c](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds C source compilation capabilities to a project.
- [cpp](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds C++ source compilation capabilities to a project.
- [objective-c](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds Objective-C source compilation capabilities to a project.
- [objective-cpp](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds Objective-C++ source compilation capabilities to a project.
- [gradle-retrolambda](https://github.com/evant/gradle-retrolambda) - Get Java lambda support in Java 6, 7 and Android.
- [clojurephant](https://github.com/clojurephant/clojurephant) - Clojure/ClojureScript support for Gradle

### Code quality

- [findbugs](https://docs.gradle.org/current/userguide/findbugs_plugin.html) - Official plugin that performs quality checks on Java source files using [FindBugs](http://findbugs.sourceforge.net/).
- [spotbugs](https://plugins.gradle.org/plugin/com.github.spotbugs) - Official plugin that performs quality checks on Java source files using [SpotBugs](https://spotbugs.github.io/).
- [checkstyle](https://docs.gradle.org/current/userguide/checkstyle_plugin.html) - Official plugin that performs quality checks on Java source files using [Checkstyle](http://checkstyle.sourceforge.net/index.html).
- [spotless](https://github.com/diffplug/spotless/tree/master/plugin-gradle) - Checks and applies formatting rules using the Eclipse, google-java-format, ktlint, scalafmt, and also user-defined rules.
- [pmd](https://docs.gradle.org/current/userguide/pmd_plugin.html) - Official plugin that performs quality checks on your project's Java source files using [PMD](http://pmd.sourceforge.net/).
- [jdepend](https://docs.gradle.org/current/userguide/jdepend_plugin.html) - Official plugin that performs quality checks on your project's source files using [JDepend](http://clarkware.com/software/JDepend.html).
- [codenarc](https://docs.gradle.org/current/userguide/codenarc_plugin.html) - Official plugin that Performs quality checks on Groovy source files using [CodeNarc](http://codenarc.sourceforge.net/index.html).
- [jacoco](https://docs.gradle.org/current/userguide/jacoco_plugin.html) - Official plugin that provides integration with the [JaCoCo](http://www.eclemma.org/jacoco/) code coverage library for Java.
- [gradle-cobertura-plugin](https://github.com/stevesaliman/gradle-cobertura-plugin) - Use cobertura.
- [coveralls-gradle-plugin](https://github.com/kt3k/coveralls-gradle-plugin) - Send coverage data to [coveralls.io](https://coveralls.io/).
- [gradle-scoverage](https://github.com/scoverage/gradle-scoverage) - Enable the use of Scoverage in a Gradle Scala project.
- [gradle-errorprone-plugin](https://github.com/tbroyer/gradle-errorprone-plugin) - Use the [error-prone](https://github.com/google/error-prone) compiler for Java.
- [gradle-spelling-plugin](https://github.com/ksoichiro/gradle-spelling-plugin) - Inspect spelling using custom blacklist.
- [gradle-modernizer-plugin](https://github.com/simonharrer/gradle-modernizer-plugin) - Detect uses of legacy Java APIs.

### Code generation

- [gradle-protobuf-plugin](https://github.com/tcawley/gradle-protobuf-plugin) - Compile [Google Protocol Buffers](https://developers.google.com/protocol-buffers/) files.
- [querydsl-plugin](https://github.com/ewerk/gradle-plugins/tree/master/querydsl-plugin) - Generate [Querydsl](http://www.querydsl.com/) classes.

### Java application development

- [gradle-apt-plugin](https://github.com/tbroyer/gradle-apt-plugin) - Make it easier/safer to use Java annotation processors.
- [vertx-gradle-plugin](https://github.com/darylteo/vertx-gradle-plugin) - Unofficial plugin for starting Vert.x projects.

### Web application development

- [spring-boot](http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#build-tool-plugins-gradle-plugin) - Provide Spring Boot support.
- [gretty](https://github.com/akhikhl/gretty) - Run web apps on jetty and tomcat.
- [gradle-tomcat-plugin](https://github.com/bmuschko/gradle-tomcat-plugin) - Support deployment of your web application to an embedded Tomcat web container.
- [gradle-jrebel-plugin](https://github.com/zeroturnaround/gradle-jrebel-plugin) - Generate rebel.xml configuration file.
- [gradle-js-plugin](https://github.com/eriwen/gradle-js-plugin) - Manage JavaScript.
- [gradle-jslint-plugin](https://github.com/kellyrob99/gradle-jslint-plugin) - Run JSLint static analysis against JavaScipt code.
- [gradle-node-plugin](https://github.com/srs/gradle-node-plugin) - Run NodeJS scripts.
- [gradle-gulp-plugin](https://github.com/srs/gradle-gulp-plugin) - Run Gulp tasks.
- [gradle-grunt-plugin](https://github.com/srs/gradle-grunt-plugin) - Run Grunt tasks.
- [bower-installer-plugin](https://github.com/craigburke/bower-installer-gradle) - Manage client-side dependencies.
- [apina](https://github.com/EvidentSolutions/apina) - Creates client-side TypeScript from server-side APIs.
- [asset-pipeline](https://github.com/bertramdev/asset-pipeline) - Manage and process static assets in JVM applications.
- [gradle-web-resource-plugin](https://github.com/ksoichiro/gradle-web-resource-plugin) - Use CoffeeScript, LESS and Bower libraries without Node.js/npm.
- [gradle-compass](https://github.com/robfletcher/gradle-compass) - Compile and watche SASS files.
- [rest-gradle-plugin](https://github.com/noamt/rest-gradle-plugin) - Perform REST requests.

### Android application development

- Dependency management
  - [sdk-manager-plugin](https://github.com/JakeWharton/sdk-manager-plugin) - Download and manage Android SDK.
  - [android-native-dependencies](https://github.com/nhachicha/android-native-dependencies) - Gradle plugin for resolving and downloading Android native dependencies (.so)
- Alternative language
  - [groovy-android-gradle-plugin](https://github.com/groovy/groovy-android-gradle-plugin) - Support the Groovy language for building Android apps.
- APK handling
  - [dexcount-gradle-plugin](https://github.com/KeepSafe/dexcount-gradle-plugin) - Report the number of method references in APK.
  - [android-gradle-mulchannel-plugin](https://github.com/ihrthk/android-gradle-mulchannel-plugin) - Generate multiple apks from different channel.
  - [gradle-android-apk-size-plugin](https://github.com/vanniktech/gradle-android-apk-size-plugin) - Gradle plugin that generates CSV files with apk size per output and variant of an apk.
- Build variant handling
  - [gradle-advanced-build-version](https://github.com/moallemi/gradle-advanced-build-version) - Generate the Android version code and version name automatically.
  - [gradle-config](https://github.com/tmiyamon/gradle-config) - Handle variant specific settings with yaml format.
- Icons
  - [gradle-android-ribbonizer-plugin](https://github.com/gfx/gradle-android-ribbonizer-plugin) - Add a ribbon to launcher icons of Android apps.
  - [gradle-android-appiconoverlay](https://github.com/splatte/gradle-android-appiconoverlay) - Automatically overlay the app icon with the current git commit SHA1.
  - [gradle-mdicons](https://github.com/tmiyamon/gradle-mdicons) - Manage material design icons.
- Releasing
  - [gradle-deploygate-plugin](https://github.com/deploygate/gradle-deploygate-plugin) - Build and deploy apps to DeployGate.
  - [testfairy-gradle-plugin](https://github.com/testfairy/testfairy-gradle-plugin) - Official plugin to upload signed builds to TestFairy.
  - [gradle-play-publisher](https://github.com/Triple-T/gradle-play-publisher) - Manage your complete Play Store presence in your repository: Listing, Release Notes, APKs and App Bundles.
- Testing
  - [gradle-plugin-robospock](https://github.com/Centril/gradle-plugin-robospock) - Configure robospock (gradle + spock + roboelectric) easily.
  - [unmock-plugin](https://github.com/bjoernQ/unmock-plugin) - Allow you to use selected classes from a real Android-Jarfile for Android unit testing.
  - [gradle-monkey-plugin](https://github.com/AutoScout24/gradle-monkey-plugin) - Run Android monkey tests.
- Miscellaneous
  - [ormlite-android-gradle-plugin](https://github.com/stephanenicolas/ormlite-android-gradle-plugin) - Generate an ORMLite configuration file and boost DAOs creations.
  - [gradle-eclipse-aar-plugin](https://github.com/ksoichiro/gradle-eclipse-aar-plugin) - Use Android AAR libraries on Eclipse.
  - [gradle-android-git](https://github.com/ksoichiro/gradle-android-git) - Manage Git dependency for Android apps.
  - [Shot](https://github.com/Karumi/Shot) - Shot is a Gradle plugin that simplifies the execution of screenshot tests using [Screenshot Tests For Android by Facebook](http://facebook.github.io/screenshot-tests-for-android/).

### iOS and Mac application development

- [gradle-xcodePlugin](https://github.com/openbakery/gradle-xcodePlugin) - Build iOS and Mac projects.
- [j2objc-gradle](https://github.com/j2objc-contrib/j2objc-gradle) - Enable Java source to be part of an iOS application's build.

### Editor and IDE integration

- [eclipse](https://docs.gradle.org/current/userguide/eclipse_plugin.html) - Official plugin that generates files that are used by [Eclipse IDE](http://eclipse.org/).
- [idea](https://docs.gradle.org/current/userguide/idea_plugin.html) - Official plugin that generates files that are used by [Intellij IDEA IDE](http://www.jetbrains.com/idea/index.html).
- [visual-studio](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds integration with Visual Studio.
- [goomph](https://github.com/diffplug/goomph) - Downloads an Eclipse IDE with all required plugins and creates a workspace with specified settings and projects.
- [gradle-sublimetext-plugin](https://github.com/phildopus/gradle-sublimetext-plugin) - Generate Sublime Text 2 project file.
- [gradle-syntastic-plugin](https://github.com/Scuilion/gradle-syntastic-plugin) - Integrate Java project with Vim and Syntastic.

### Templating

- [markdown-gradle-plugin](https://github.com/aalmiray/markdown-gradle-plugin) - Convert Markdown to HTML.
- [gradle-twirl](https://github.com/67726e/gradle-twirl) - Provide [Twirl](https://github.com/playframework/twirl) template compilation and integration.

### Database

- [flyway-gradle-plugin](http://flywaydb.org/documentation/gradle/) - [Flyway](http://flywaydb.org/) database migration tasks.
- [liquibase-gradle-plugin](https://github.com/liquibase/liquibase-gradle-plugin) - Use [Liquibase](http://liquibase.org/) to manage your database upgrades.
- [gradle-migrations-plugin](https://github.com/marceloemanoel/gradle-migrations-plugin) - Provide gradle build integration with [mybatis migrations](https://code.google.com/p/mybatis/wiki/Migration).
- [ml-gradle](https://github.com/marklogic-community/ml-gradle) - Automate everything involving [MarkLogic](https://developer.marklogic.com/).

### Dependency management

- [gradle-versions-plugin](https://github.com/ben-manes/gradle-versions-plugin) - Provide a task to determine which dependencies have updates.
- [gradle-nuget-plugin](https://github.com/Ullink/gradle-nuget-plugin) - Execute NuGet.exe from Gradle.
- [gradle-dependency-analyze](https://github.com/wfhartford/gradle-dependency-analyze) - Dependency analysis plugin for gradle.
- [gradle-dependency-lock-plugin](https://github.com/nebula-plugins/gradle-dependency-lock-plugin) - Allow people using dynamic dependency versions to lock them to specific versions.
- [gradle-git-repo-plugin](https://github.com/layerhq/gradle-git-repo-plugin) - Use a private git repo as a Maven repository.
- [buildSrcVersions](https://github.com/jmfayard/buildSrcVersions) - Painless dependencies management.

### Debugging

- [gradle-groovysh-plugin](https://github.com/tkruse/gradle-groovysh-plugin) - Start an interactive groovy shells.

### Testing

- [gradle-gatling-plugin](https://github.com/alphagov/gradle-gatling-plugin) - Run [Gatling](http://gatling.io/) scenarios.
- [gradle-console-reporter](https://github.com/ksoichiro/gradle-console-reporter) - Report test result to console.
- [gradle-test-logger-plugin](https://github.com/radarsh/gradle-test-logger-plugin) - A Gradle plugin for printing beautiful logs on the console while running tests.
- [gradle-itest-plugin](https://github.com/Softeq/itest-gradle-plugin) - This plugin adds integration testing support to the project

### Building

- [build-time-tracker-plugin](https://github.com/passy/build-time-tracker-plugin) - Continuously track and report your build times.
- [gradle-metrics-plugin](https://github.com/nebula-plugins/gradle-metrics-plugin) - Collect Gradle build metrics and persist them to an external datastore.
- [nebula-plugin](https://nebula-plugins.github.io/) - A collection of Gradle plugins providing repeatable builds, immutable deployments and helping eliminate boilerplate code.

### Packaging

- [gradle-one-jar](https://github.com/rholder/gradle-one-jar) - Build self-contained executable jars that include all dependencies.
- [gradle-build-info-plugin](https://github.com/ksoichiro/gradle-build-info-plugin) - Include build information such as Git commit ID to your JAR.
- [gradle-replacer](https://github.com/ksoichiro/gradle-replacer) - Provide a minimalistic template engine feature.

### Releasing

- [gradle-ssh-plugin](https://github.com/int128/gradle-ssh-plugin) - Provide SSH facilities for continuous delivery.
- [maven](https://docs.gradle.org/current/userguide/maven_plugin.html) - Official plugin that adds support for publishing artifacts to Maven repositories.
- [plugin-publish](https://plugins.gradle.org/plugin/com.gradle.plugin-publish) - Publish plugins to the Gradle Plugin Portal.
- [gradle-bintray-plugin](https://github.com/bintray/gradle-bintray-plugin) - Publish artifacts to Bintray.
- [gradle-nexus-plugin](https://github.com/bmuschko/gradle-nexus-plugin) - Configure and upload artifacts to Sonatype Nexus.
- [gradle-release](https://github.com/researchgate/gradle-release) - Automate releasing process. Similar to the Maven release plugin.
- [spotless-changelog](https://github.com/diffplug/spotless-changelog) - Parses changelog to calculate next version, then updates changelog on publish.

### Notification

- [announce](https://docs.gradle.org/current/userguide/announce_plugin.html) - Official plugin that publishes messages to platforms such as Twitter or Growl.
- [gradle-slack-plugin](https://github.com/Mindera/gradle-slack-plugin) - Send messages to Slack after each build.

### Cloud services

- [gradle-aws-plugin](https://github.com/classmethod-aws/gradle-aws-plugin) - Manage AWS resouces.
- [gradle-s3-plugin](https://github.com/skhatri/gradle-s3-plugin) - Upload files to / download files from S3.
- [gradle-stash-plugin](https://github.com/nebula-plugins/gradle-stash-plugin) - Interact with the Stash SCM.
- [gradle-cf-plugin](https://github.com/melix/gradle-cf-plugin) - Interact with CloudFoundry.

### SCM

- [gradle-git](https://github.com/ajoberstar/gradle-git) - Set of plugin to interact with Git repositories, publish files to gh-page, etc.
- [gradle-svntools-plugin](https://github.com/martoe/gradle-svntools-plugin) - Provide various SVN-related tasks.
- [gradle-snapshot-plugin](https://github.com/novabyte/gradle-snapshot-plugin) - Generate build metadata from SCM tools.

### CI

- [build-info](https://github.com/jfrogdev/build-info) - Artifactory's open integration layer for the CI servers and build tools.

### VM and container

- [gradle-vagrant-plugin](https://github.com/bmuschko/gradle-vagrant-plugin) - Manage Vagrant boxes.
- [bmuschko/gradle-docker-plugin](https://github.com/bmuschko/gradle-docker-plugin) - Gradle plugin for managing Docker images and containers.
- [nebula-docker-plugin](https://github.com/nebula-plugins/nebula-docker-plugin) - Nebula gradle plugin for reducing boilerplate in creating docker images.
- [palantir/gradle-docker](https://github.com/palantir/gradle-docker) - Build and push Docker images.
- [Transmode/gradle-docker](https://github.com/Transmode/gradle-docker) - Build Docker images.

## Boilerplates

- [android-gradle-template](https://github.com/nenick/android-gradle-template) - Template project for developing Android app.
- [vertx-gradle-template](https://github.com/vert-x/vertx-gradle-template) - Template project for developing Vert.x module.
- [gradle-plugin-starter](https://github.com/int128/gradle-plugin-starter) - Template project for developing Gradle plugin.
- [gatling-with-gradle](https://github.com/RallySoftware/gatling-with-gradle) - Sample project that demonstrates how to automate load testing with [Gatling](http://gatling.io/).

## Resources

### General Resources

- [GitHub Repository](https://github.com/gradle/gradle)
- [Gradle Forums](https://discuss.gradle.org/)
- [Gradle Plugin Portal](https://plugins.gradle.org/)

### Official Documentation

- [User Guide](https://docs.gradle.org/current/userguide/userguide.html)
- [DSL Reference](https://docs.gradle.org/current/dsl/)

## Contribution

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Soichiro Kashima](https://github.com/ksoichiro) has waived all copyright and related or neighboring rights to this work.
