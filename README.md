# lombok-publisher
lombok daily snapshot builds for everyone

[![Build Status](https://travis-ci.org/iherasymenko/lombok-publisher.svg?branch=master)](https://travis-ci.org/iherasymenko/lombok-publisher)
[ ![Download](https://api.bintray.com/packages/iherasymenko/lombok/lombok-snapshots/images/download.svg) ](https://bintray.com/iherasymenko/lombok/lombok-snapshots/_latestVersion)

## Maven settings.xml
```
<profiles>
	<profile>
		<repositories>
			<repository>
				<snapshots>
					<enabled>false</enabled>
				</snapshots>
				<id>bintray-iherasymenko-lombok</id>
				<name>bintray</name>
				<url>https://dl.bintray.com/iherasymenko/lombok</url>
			</repository>
		</repositories>	
		<id>bintray</id>
	</profile>
</profiles>
<activeProfiles>
	<activeProfile>bintray</activeProfile>
</activeProfiles>
```