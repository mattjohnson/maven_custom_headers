
Looking at [HttpClient HTTP Wagon](https://maven.apache.org/guides/mini/guide-http-settings.html#Maven_3.0.4) it seems 
like we should be able to add headers to requests but I can't seem to get this to work. A custom settings.xml file is
included in this repo that should have the configuration. Also, added http-wagon in the pom.xml build extensions.

Using `mvn dependency:purge-local-repository --settings settings.xml` to download dependencies from NXRM for each test.