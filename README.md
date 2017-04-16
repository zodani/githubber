# GitHubber
GitHub Android Application.

# Dependencies
* MVP
* RxJava, RxAndroid
* Retrolambda
* AndroidAnnotations(AA)
* Retrofit2, OkHttp3
* Glide
* Lombok

# Build
### Lombok
1. Go to File > Settings > Plugins
2. Click on Browse repositories...
3. Search for Lombok plugin.
4. Click on Install plugin.
5. Restart Android Studio.
6. Go to File > Other Settings > Default Settings... > Build, Execution, Deployment
7. Compiler > Annotation Processors > Check "Enable annotation processing"

### Properties
1. Go to github developers site and [Register](https://github.com/settings/developers) a new application.
2. Save Client ID, Client Secret
3. Create gradle.properties to root directory.
4. Declare variables into gradle.properties.
```gradle
CLIENT_ID="Insert client_id"
CLIENT_SECRET="Insert client_secret"
```