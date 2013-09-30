Looking at the FHIR build process... incrementally.

Rebuild client + reload:
```
./gradlew generateDocs -PfhirBuildDir=/path/to/fhir/svn/trunk/build
```

Generate resource .htm without rebuilding client:
```
./gradlew generteResources -PfhirBuildDir=/path/to/fhir/svn/trunk/build
```
