<!--

********************************************************************************

WARNING:

    DO NOT EDIT "sonarqube/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "sonarqube/" combined with a set of templates)

********************************************************************************

-->

# Quick reference

-	**Maintained by**:  
	[SonarSource](https://github.com/SonarSource/docker-sonarqube)

-	**Where to get help**:  
	[the SonarSource Community forum](https://community.sonarsource.com/tags/c/help/sq/docker), [the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://blog.docker.com/2016/11/introducing-docker-community-directory-docker-community-slack/), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

# Supported tags and respective `Dockerfile` links

-	[`2025.3.1-developer`, `2025.3-developer`, `developer`](https://github.com/SonarSource/docker-sonarqube/blob/e29feb48414fb0f210d4d025158b7557eefe0092/commercial-editions/developer/Dockerfile)

-	[`2025.3.1-enterprise`, `2025.3-enterprise`, `enterprise`](https://github.com/SonarSource/docker-sonarqube/blob/e29feb48414fb0f210d4d025158b7557eefe0092/commercial-editions/enterprise/Dockerfile)

-	[`2025.3.1-datacenter-app`, `2025.3-datacenter-app`, `datacenter-app`](https://github.com/SonarSource/docker-sonarqube/blob/e29feb48414fb0f210d4d025158b7557eefe0092/commercial-editions/datacenter/app/Dockerfile)

-	[`2025.3.1-datacenter-search`, `2025.3-datacenter-search`, `datacenter-search`](https://github.com/SonarSource/docker-sonarqube/blob/e29feb48414fb0f210d4d025158b7557eefe0092/commercial-editions/datacenter/search/Dockerfile)

-	[`2025.1.3-developer`, `2025.1-developer`, `2025-lta-developer`](https://github.com/SonarSource/docker-sonarqube/blob/2a5b137d0669b87f7dfe6c295a5078d7d7c1aaaf/commercial-editions/developer/Dockerfile)

-	[`2025.1.3-enterprise`, `2025.1-enterprise`, `2025-lta-enterprise`](https://github.com/SonarSource/docker-sonarqube/blob/2a5b137d0669b87f7dfe6c295a5078d7d7c1aaaf/commercial-editions/enterprise/Dockerfile)

-	[`2025.1.3-datacenter-app`, `2025.1-datacenter-app`, `2025-lta-datacenter-app`](https://github.com/SonarSource/docker-sonarqube/blob/2a5b137d0669b87f7dfe6c295a5078d7d7c1aaaf/commercial-editions/datacenter/app/Dockerfile)

-	[`2025.1.3-datacenter-search`, `2025.1-datacenter-search`, `2025-lta-datacenter-search`](https://github.com/SonarSource/docker-sonarqube/blob/2a5b137d0669b87f7dfe6c295a5078d7d7c1aaaf/commercial-editions/datacenter/search/Dockerfile)

-	[`25.7.0.110598-community`, `community`, `latest`](https://github.com/SonarSource/docker-sonarqube/blob/4c717b6de25b4882074a79d7f02447004df555cf/community-build/Dockerfile)

-	[`9.9.8-community`, `9.9-community`, `9-community`, `lts`, `lts-community`](https://github.com/SonarSource/docker-sonarqube/blob/4c717b6de25b4882074a79d7f02447004df555cf/9/community/Dockerfile)

-	[`9.9.8-developer`, `9.9-developer`, `9-developer`, `lts-developer`](https://github.com/SonarSource/docker-sonarqube/blob/4c717b6de25b4882074a79d7f02447004df555cf/9/developer/Dockerfile)

-	[`9.9.9-enterprise`, `9.9-enterprise`, `9-enterprise`, `lts-enterprise`](https://github.com/SonarSource/docker-sonarqube/blob/4c717b6de25b4882074a79d7f02447004df555cf/9/enterprise/Dockerfile)

-	[`9.9.9-datacenter-app`, `9.9-datacenter-app`, `9-datacenter-app`, `lts-datacenter-app`](https://github.com/SonarSource/docker-sonarqube/blob/4c717b6de25b4882074a79d7f02447004df555cf/9/datacenter/app/Dockerfile)

-	[`9.9.9-datacenter-search`, `9.9-datacenter-search`, `9-datacenter-search`, `lts-datacenter-search`](https://github.com/SonarSource/docker-sonarqube/blob/4c717b6de25b4882074a79d7f02447004df555cf/9/datacenter/search/Dockerfile)

# Quick reference (cont.)

-	**Where to file issues**:  
	[https://github.com/SonarSource/docker-sonarqube/issues](https://github.com/SonarSource/docker-sonarqube/issues?q=)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/sonarqube/), [`arm64v8`](https://hub.docker.com/r/arm64v8/sonarqube/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/sonarqube/` directory](https://github.com/docker-library/repo-info/blob/master/repos/sonarqube) ([history](https://github.com/docker-library/repo-info/commits/master/repos/sonarqube))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images repo's `library/sonarqube` label](https://github.com/docker-library/official-images/issues?q=label%3Alibrary%2Fsonarqube)  
	[official-images repo's `library/sonarqube` file](https://github.com/docker-library/official-images/blob/master/library/sonarqube) ([history](https://github.com/docker-library/official-images/commits/master/library/sonarqube))

-	**Source of this description**:  
	[docs repo's `sonarqube/` directory](https://github.com/docker-library/docs/tree/master/sonarqube) ([history](https://github.com/docker-library/docs/commits/master/sonarqube))

# What is `sonarqube`?

`sonarqube` Docker repository stores the official Sonar images for SonarQube Server and SonarQube Community Build.

[SonarQube Server](https://www.sonarsource.com/products/sonarqube/) (formerly SonarQube) is an on-premise analysis tool designed to detect quality and security issues in 30+ languages, frameworks, and IaC platforms. The solution also provides fix recommendations leveraging AI with Sonar's AI CodeFix capability. By integrating directly with your CI pipeline or on one of the supported DevOps platforms, your code is checked against an extensive set of rules that cover many attributes of code, such as maintainability, reliability, and security issues on each merge/pull request.

[SonarQube Community Build](https://www.sonarsource.com/open-source-editions/sonarqube-community-edition/) (formerly SonarQube Community) is Sonar's self-managed free offering, released on a monthly schedule. It includes the latest core capabilities available in open source, providing essential features such as bug detection, identification of code smells, and basic security issue analysis across 21 programming languages and frameworks. For advanced security analysis, enterprise-grade integrations, and scalability features, the commercial version, SonarQube Server, is available.

## How to use this image

Here, you'll find the Docker images for the SonarQube Server (Developer Edition, Enterprise Edition, and Data Center Edition), as well as for SonarQube Community Build.

## Docker Host Requirements

Because SonarQube uses an embedded Elasticsearch, make sure that your Docker host configuration complies with the [Elasticsearch production mode requirements](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-cli-run-prod-mode) and [File Descriptors configuration](https://www.elastic.co/guide/en/elasticsearch/reference/current/file-descriptors.html).

For example, on Linux, you can set the recommended values for the current session by running the following commands as root on the host:

```console
sysctl -w vm.max_map_count=524288
sysctl -w fs.file-max=131072
ulimit -n 131072
ulimit -u 8192
```

## Demo

To quickly run a demo instance, see Using Docker on the [Try Out SonarQube](https://docs.sonarsource.com/sonarqube-server/latest/try-out-sonarqube/) page. When you are ready to move to a more sustainable setup, take some time to read the **Installation** and **Configuration** sections below.

## Installation

> **Multi-platform support**: Starting from SonarQube `9.9` LTS, the docker images support running both on `amd64` architecture and `arm64`-based Apple Silicon (M1).

For installation instructions, see Installing the Server from the Docker Image on the [Install the Server](https://docs.sonarsource.com/sonarqube-server/latest/setup-and-upgrade/install-the-server/installing-sonarqube-from-docker/) page.

To run a cluster with the SonarQube Server Data Center Edition, please refer to Installing SonarQube Server from the Docker Image on the [Install the Server as a Cluster](https://docs.sonarsource.com/sonarqube-server/latest/setup-and-upgrade/install-the-server-as-a-cluster/) page.

> The `lts` tag on Docker images is replaced with every new LTS release. If you want to avoid any automatic major upgrades, we recommend using the corresponding `9.9-<edition>` tag instead of `lts-<edition>`.

## Configuration

### Port binding

By default, the server running within the container will listen on port 9000. You can expose the container port 9000 to the host port 9000 with the `-p 9000:9000` argument to `docker run`, like the command below:

```console
docker run --name sonarqube-custom -p 9000:9000 sonarqube:community
```

You can then browse to `http://localhost:9000` or `http://host-ip:9000` in your web browser to access the web interface.

### Database

By default, the image will use an embedded H2 database that is not suited for production.

> **Warning:** Only a single instance of SonarQube Server or SonarQube Community Build can connect to a database schema. If you're using a Docker Swarm or Kubernetes, make sure that multiple instances are never running on the same database schema simultaneously. This will cause the SonarQube to behave unpredictably, and data will be corrupted. There is no safeguard, as described on [SONAR-10362](https://jira.sonarsource.com/browse/SONAR-10362). The SonarQube Server Data Center Edition has the same limitation in that only one cluster can connect to one database schema at the same time.

Set up a database by following the ["Installing the Database"](https://docs.sonarsource.com/sonarqube-server/latest/setup-and-upgrade/install-the-server/installing-the-database/) section.

### Use volumes

We recommend creating volumes for the following directories:

-	`/opt/sonarqube/data`: data files, such as the embedded H2 database and Elasticsearch indexes
-	`/opt/sonarqube/logs`: contains SonarQube logs about access, web process, CE process, Elasticsearch logs
-	`/opt/sonarqube/extensions`: for 3rd party plugins

> **Warning:** You cannot use the same volumes on multiple instances of SonarQube.

## Upgrading

For upgrade instructions, see Upgrading from the Docker Image on the [Upgrade the Server](https://docs.sonarsource.com/sonarqube-server/latest/server-upgrade-and-maintenance/upgrade/upgrade/) page.

## Advanced configuration

### Customized image

In some environments, it may make more sense to prepare a custom image containing your configuration. A `Dockerfile` to achieve this may be as simple as:

```dockerfile
FROM sonarqube:community
COPY sonar-custom-plugin-1.0.jar /opt/sonarqube/extensions/
```

You could then build and try the image with something like:

```console
$ docker build --tag=sonarqube-custom .
$ docker run -ti sonarqube-custom
```

### Avoid hard termination

The instance will stop gracefully, waiting for any tasks in progress to finish. Waiting for in-progress tasks to finish can take a large amount of time, which the docker does not expect by default when stopping. To avoid having the instance killed by the Docker daemon after 10 seconds, it is best to configure a timeout to stop the container with `--stop-timeout`. For example:

```console
docker run --stop-timeout 3600 sonarqube
```

## Administration

Information about administering your instance of SonarQube Server begins [here](https://docs.sonarsource.com/sonarqube-server/latest/instance-administration/overview/).

# License

SonarQube Community Build is licensed under [GNU Lesser General Public License, Version 3.0](http://www.gnu.org/licenses/lgpl.txt). SonarQube Server Developer, Enterprise, and Data Center Editions are licensed under [SonarSource Terms and Condition](https://www.sonarsource.com/docs/sonarsource_terms_and_conditions.pdf).

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `sonarqube/` directory](https://github.com/docker-library/repo-info/tree/master/repos/sonarqube).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
