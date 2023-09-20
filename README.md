Reproduce Issue https://github.com/JetBrains/compose-multiplatform/issues/3437

To reproduce: `./gradlew :shared:compileIosMainKotlinMetadata`

Change `implementation(compose.runtime)` to `api(compose.runtime)` fixes this problem
