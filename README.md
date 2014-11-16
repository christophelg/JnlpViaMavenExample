# JNLP via Maven

This project is meant to show how to use the various maven plugins to produce a war file for a JNLP application.

## Motivation

Unfortunately, some companies are still using JNLP to deploy applications, 
and it is extremely difficult to configure maven to produce a war file that will deploy your application via JNLP.

## Solution

The project is composed of 2 projects
* a trivial swing application so that we have something to deploy
* a war project that contains the configuration complexity

## External References

[Someone Else Journey](http://www.shaunabram.com/swing-webstart-maven-example/)
[webstart-maven-plugin Documentation](http://mojo.codehaus.org/webstart/webstart-maven-plugin/jnlp-mojos-overview.html)
