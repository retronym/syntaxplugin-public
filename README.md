A fork of [JIRA Syntax Highlighter PlugIn](https://bitbucket.org/hski/syntaxplugin-public/wiki/Home)

## Motivation

 - We want the default language for code blocks on issues.scala-lang.org to be Scala!
 - Line numbers are too noisy to be shown by default

## Build

Install the [Atlassian SDK](https://developer.atlassian.com/display/DOCS/Install+the+Atlassian+SDK+on+a+Linux+or+Mac+System)

```
% atlas-mvn install
% ls -la target/syntaxplugin-1.7.1-SCALA.jar
-rw-r--r--  1 jason  staff  151792 Sep 27 15:01 target/syntaxplugin-1.7.1-SCALA.jar
```

Install that JAR as a plugin in JIRA, following install instructions from the plugin's documentation.

Voila!
