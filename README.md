# Reddit

## Deploy the connector

Make sure to `cd` to the root folder of the repo. In there, execute the following Power Platform CLI command to deploy it to the environment the current auth profile is connected to:

`pac connector create --api-definition-file ./apiDefinition.json --api-properties-file ./apiProperties.json`

## Update the connector

Make sure to `cd` to the root folder of the repo. In there, modify the following Power Platform CLI command so that it points to the right connector ID and execute it to update it in the environment the current auth profile is connected to:

`pac connector update --connector-id 00000000-0000-0000-0000-000000000000 --api-definition-file ./apiDefinition.json`
