# Extended Power Platform CoE Pipeline Templates v2
_Original author: Alex MacVean 2022-2024_

Explanation blog: https://www.linkedin.com/pulse/best-alm-strategy-power-platform-pro-devs-alexander-macvean-r0l3e 

# Extended ALM
Create pipelines from these templates to enact the Extended ALM 
###Power Platform Solutions:
- Export power platform solution from dev to source control: **pipelines/pp-export-pp-solution.yml**
- Build power platform solution package from source control and publish to artifact feed: **pipelines/pp-build-and-publish-solution.yml**

###Config Data:
- Export config data from dev to source control: **pipelines/pp-extract-data.yml**
- Build config data package from source control and publish to artifact feed: **pipelines/pp-build-and-publish-configuration-data.yml**

###Deployments:
- Create new power platform environment: **pipelines/pp-create-pp-env-hardcoded.yml**
- Deploy packages from artifact feed to target environments: **pipelines/pp-deploy-packages-from-manifest.yml**
