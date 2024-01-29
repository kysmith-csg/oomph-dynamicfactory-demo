# Oomph Dynamic Factory Demo
This repository contains a tycho-pomless setup to demo pull request https://github.com/eclipse-oomph/oomph/pull/61 to allow Oomph to import Maven projects without a pom.xml file.

To see it in action, set a breakpoint on `MavenImportTaskImpl` line 477 and you will see the `DynamicMavenProjectFactory` using an alternate `pom.xml` filename instead.