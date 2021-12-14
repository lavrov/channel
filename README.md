# Coursier channel

Descriptors for my cli apps.

```sh
coursier channel --add https://git.io/JTxCg
coursier install src
```

*Note:*
In order for installation to work you need github access token with _read:packages_ permission.

Configure github access via [_credentials.properties_](https://get-coursier.io/docs/other-credentials#property-file).
```
github.username=lavrov
github.password=<GITHUB_TOKEN>
github.host=maven.pkg.github.com
```

Token will not be required when [this issue](https://github.community/t/download-from-github-package-registry-without-authentication/14407) is solved.
