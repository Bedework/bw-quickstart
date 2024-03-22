# bw-quickstart
Components mostly needed for a quickstart/demo distribution

### Requirements

1. JDK 17
2. Maven 3

### Building Locally

> mvn clean install

### Releasing

Releases of this fork are published to Maven Central via Sonatype.

To create a release, you must have:

1. Permissions to publish to the `org.bedework` groupId.
2. `gpg` installed with a published key (release artifacts are signed).

To perform a new release use the release script:

> ./bedework/build/quickstart/linux/util-scripts/release.sh <module-name> "<release-version>" "<new-version>-SNAPSHOT"

When prompted, indicate all updates are committed

For full details, see [Sonatype's documentation for using Maven to publish releases](http://central.sonatype.org/pages/apache-maven.html).

### Release Notes
#### 4.0.0
* Initial release

#### 4.0.1
* Issues after problems with release of 4.0.0

#### 4.0.2
* Update library versions
* Add missing table to CalDb
* Upgrade to opensearch 2.1.0
