## Oomph Development
#### 1. redirection for local test in eclipse.ini
```
-Doomph.redirection.index.redirection=index:/->file:///c:/Users/D054341/git/internal-oomph/setups/
```
#### 2. import [THIS](https://github.wdf.sap.corp/nextgenpayroll-zugspitze-infrastructure/internal-oomph) project as "generic project" to Eclipse
#### 3. make changes
#### 4. test changes by importing oomph project, like [this](https://github.wdf.sap.corp/nextgenpayroll-zugspitze-infrastructure/internal-ngp-devbox/blob/master/README.md#3-open-eclipse-and-do-the-following)
#### 5. submit the changes


## redirection for distribution VM eclipse.ini
```
-Doomph.redirection.index.redirection=index:/->https://github.wdf.sap.corp/raw/nextgenpayroll-zugspitze-infrastructure/internal-oomph/master/setups/
```
This means, whenever there is a change in this repo, the distributed VMs will get the changes automatically.
