# spring-boot7

Spring Boot Maven service scaffolded by Red Hat Developer Hub.

## Package

- **Group ID:** `io.demo`
- **Artifact ID:** `springbootapp7`
- **Namespace:** `spring-demos`

## Where to look in Developer Hub

| Tab / area | What it shows |
|------------|----------------|
| **CI** | GitHub Actions runs from this repository |
| **Issues** | GitHub Issues for the repo |
| **CD** | Argo CD Application `spring-boot7` |
| **Topology / Kubernetes** | Workload in `spring-demos` |
| **Image Registry** | Quay demo image (`openshifttest/hello-openshift`) until CI pushes your build |
| **Docs** | These TechDocs pages |
| **ServiceNow** | Incidents linked with entity id `spring-boot7` |

## Local build

```bash
mvn -B test package
```

GitHub Actions CI uses the same Maven flow (wrapper jar in the skeleton is incomplete, so CI uses `setup-java`’s Maven).
