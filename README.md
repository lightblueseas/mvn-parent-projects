# Overview

<div align="center">

[![license apache2](https://img.shields.io/badge/license-apache2-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/lightblueseas/mvn-parent-projects.svg?branch=master)](https://travis-ci.org/lightblueseas/mvn-parent-projects)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-parent-projects/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.alpharogroup/mvn-parent-projects)
[![Open Issues](https://img.shields.io/github/issues/lightblueseas/mvn-parent-projects.svg?style=flat)](https://github.com/lightblueseas/mvn-parent-projects/issues) 

</div>

This project holds parent projects that holds general properties for specific maven projects.

## Key features:

1. Provides several plugins in the pluginManagement section that are useful for maven projects.
2. Provides several dependencies in the dependencyManagement section that are useful for maven projects.

## License

The source code comes under the liberal Apache License V2.0, making mvn-parent-projects great for all types of  applications.

## How to use it

Add as parent project in the `pom.xml` file:

	<parent>
		<groupId>de.alpharogroup</groupId>
		<artifactId>mvn-parent-projects</artifactId>
		<version>1.22</version>
		<relativePath></relativePath>
	</parent>	
	
You can find tips or errata on in the [project's wiki page](https://github.com/lightblueseas/mvn-parent-projects/wiki).

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

To share your changes, [submit a pull request](https://github.com/lightblueseas/mvn-parent-projects/pull/new/develop).

## Contacting the Developers

Do not hesitate to contact the mvn-parent-projects developers with your questions, concerns, comments, bug reports, or feature requests.
- Feature requests, questions and bug reports can be reported at the [issues page](https://github.com/lightblueseas/mvn-parent-projects/issues).

## Note

No animals were harmed in the making of this library.

# Donations

If you like this library, please consider a donation through paypal: <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B37J9DZF6G9ZC" target="_blank">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" alt="PayPal this" title="PayPal – The safer, easier way to pay online!" border="0" />
</a>

or over bitcoin or bitcoin-cash with:

1Jzso5h7U82QCNmgxxSCya1yUK7UVcSXsW

or over ether with:

0xaB6EaE10F352268B0CA672Dd6e999C86344D49D8

or over flattr: <a href="https://flattr.com/submit/auto?fid=r7vp62&url=https%3A%2F%2Fgithub.com%2Flightblueseas%2Fmvn-parent-projects" target="_blank">
<img src="http://button.flattr.com/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0">
</a>

## Credits

|Travis CI|
|:-:|
|![Travis CI](https://travis-ci.com/images/logos/TravisCI-Full-Color.png)|
|Many thanks to [Travis CI](https://travis-ci.org) for providing a free continuous integration service for open source projects.|

