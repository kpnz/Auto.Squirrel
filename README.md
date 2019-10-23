# **Squirrel Package Manager**

___

#### This utility is useful to create installer based on **[Squirrel.Windows](https://github.com/Squirrel/Squirrel.Windows)**.

The main purpose is to fully automatize the application deploy, from build to upload the updated files. App ID (`AssemblyTitle`), Title (`AssemblyTitle`), Author (`AssemblyCompany`), Description (`AssemblyDescription`) and Version (`AssemblyVersion`) are all read from the Main exe assembly information
____

### With a single mouse click you can :

1. **Update Application Version** the package version is extracted from exe file , you don't need to set this value manually. Right click on a file and select refresh version to update while running.

2. **Create Squirrel Package** . In similar way you do with Nuget Package Manager, just drag the file you want into window. No need to create lib/net45 folder.

3. **Upload installer files** . Set connection details one time - Supports local file system and Amazon Web Services S3 Buckets **[Create Account](https://console.aws.amazon.com/s3/home?region=us-west-2)**.

4. **Decide to upload only the updated files or do complete setup upload**

____

 ## Read also :


* **[Project Version Auto-Increment](docs/VersionAutoIncrement.md)** (NOTE: must follow Semantic versioning i.e. Major.Minor.Build http://semver.org/)

* **[Update Manager Integration](docs/SquirrelIntegration.md)**

* **[Squirrel Package Creation](docs/PackageCreation.md)**

___

 ![](docs/images/squirrel_upload.png)
___


## TODOS

- [ ] Button to abort upload
- [ ] Filter out unwanted files from installer list
- [ ] Check if same filename is present in same directory
