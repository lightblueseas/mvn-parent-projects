# mvn-parent-projects

This project holds parent projects that holds general properties for specific maven projects.

## Key features:

1. Provides several plugins in the pluginManagement section that are useful for maven projects.
2. Provides several dependencies in the dependencyManagement section that are useful for maven projects.

## License

The source code comes under the liberal Apache License V2.0, making mvn-parent-projects great for all types of  applications.

## Build status
[![Build Status](https://travis-ci.org/lightblueseas/mvn-parent-projects.svg?branch=master)](https://travis-ci.org/lightblueseas/mvn-parent-projects)


## Maven Central

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-parent-projects/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-parent-projects)

## How to use it

Add as parent project in the `pom.xml` file:

	<parent>
		<groupId>de.alpharogroup</groupId>
		<artifactId>mvn-parent-projects</artifactId>
		<version>1.8.0</version>
		<relativePath></relativePath>
	</parent>	

## Documentation and Examples

In this parent project there is only one profile for for releasing artifacts (projects) on sonatype. The name of the profile is 'oss.sonatype.org-staged-release' and is self-explaining.

From the shell you can execute it with the following command:
```shell
:~$ mvn clean deploy -Poss.sonatype.org-staged-release
```
This is executed on this project or in a project that have this project as parent or parent of parent and so on. A detailed description how to use it is [here](https://github.com/lightblueseas/mvn-parent-projects/issues/2).


## Want to Help and improve it? ###

The source code for mvn-parent-projects are on GitHub. Please feel free to fork and send pull requests!

Create your own fork of [lightblueseas/mvn-parent-projects/fork](https://github.com/lightblueseas/mvn-parent-projects/fork)

To share your changes, [submit a pull request](https://github.com/lightblueseas/mvn-parent-projects/pull/new/master).

## Contacting the Developers

Do not hesitate to contact the mvn-parent-projects developers with your questions, concerns, comments, bug reports, or feature requests.
- Feature requests, questions and bug reports can be reported at the [issues page](https://github.com/lightblueseas/mvn-parent-projects/issues).

## Note

No animals were harmed in the making of this library.

# Donate

If you like this library, please consider a donation through 
<a href="https://flattr.com/submit/auto?fid=r7vp62&url=https%3A%2F%2Fgithub.com%2Flightblueseas%2Fmvn-parent-projects" target="_blank">
<img src="http://button.flattr.com/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0">
</a>

