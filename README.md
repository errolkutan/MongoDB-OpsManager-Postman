# MongoDB-OpsManager-Postman

This repository contains a Postman Collection for the MongoDB Ops Manager API. 


## Endpoints

This section lists the endpoint categories contained in the collection:

- [Deployments](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/deployments/)
- [Agents](https://www.mongodb.com/docs/ops-manager/current/reference/api/agents/)
- [Measurements and Alerts](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/measurements-and-alerts/)
- [Projects and Users](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/groups-and-users/)
- [Programmatic API Key](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/prog-api-keys/)
- [Organizations and Teams](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/organizations-and-teams/)
- [Backup and Restore](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/backup-and-restore/)
- [Automation](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/automation/)
- Server Pools (Removed)
- [Version Manifest](https://www.mongodb.com/docs/ops-manager/current/reference/api/version-manifest/)
- [Log Collection Jobs](https://www.mongodb.com/docs/ops-manager/current/reference/api/log-collection/)
- [MongoDB Server Usage](https://www.mongodb.com/docs/ops-manager/current/reference/api/usage/)
- [Diagnostic Archives](https://www.mongodb.com/docs/ops-manager/current/reference/api/diagnostic-archives/)
- [Feature Control Policies](https://www.mongodb.com/docs/ops-manager/current/reference/api/feature-control-policies/)
- [Backup Administration](https://www.mongodb.com/docs/ops-manager/current/reference/api/nav/administration-backup/)


Categories remaining
- [Live Data Migration from Ops Manager to MongoDB Atlas](https://www.mongodb.com/docs/ops-manager/current/reference/api/cloud-migration/)



## Setup

### Import Collection into Postman

TODO -- add screen capture of import steps


### Create an Environment 


A Postman Environment is simply a mapping of key-value pairs whose keys are variables used in various API endpoints, speficially those used by the Ops Manager API Postman collection in this case. The following variables (case-sensitive) are required by an environment for this postman collection, but will be used by different endpoints:

- url : The url of your ops manager instance 
- apiUserName : the public API key to use for requests
- apiPass : the private API key (aka -- API secret) to use for requests
- serverId : The id of servers to use for server-specirfic requests
- hostname : The hostname to use for hostname-specific requests
- requestId : The id of the requests to use for request-specific requests
- alertId : The id of the alert to use for alert-specific requests
- clusterId : The id of the cluster to use for cluster-specific requests
- agentType : The type of the MongoDB Ops Manager agent to use for agent-specific requests 
- hostId : The id of the host to use for host specific requests
- groupName : The name of the Ops Manager group/project to use for group-specific requests
- groupId : The id of the  Ops Manager group/project to use for group-specific requests
- snapshotId : The id of the snapshot to use for snapshot-specific requests
- startDate : The start date in YYYY-MM-DDTHH:mm:SSZ format to use for log and metric extraction
- endDate : The end date in YYYY-MM-DDTHH:mm:SSZ format to use for log and metric extraction
- agentApiKey : The Agent API key to use where needed

Instructions for creating a Postman environment can be found [here](https://learning.postman.com/docs/sending-requests/managing-environments/#creating-environments). 

