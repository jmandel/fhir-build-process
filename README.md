Looking at the FHIR build process... incrementally.

Generate resource .htm without rebuilding client:
```
./gradlew generateResources -PfhirBuildDir=/path/to/fhir/svn/trunk/build
```

Generate example .htm without rebuilding client:
```
./gradlew generateExamples -PfhirBuildDir=/path/to/fhir/svn/trunk/build
```

Rebuild client + re-publish:
```
./gradlew buildAndPublish -PfhirBuildDir=/path/to/fhir/svn/trunk/build
```


