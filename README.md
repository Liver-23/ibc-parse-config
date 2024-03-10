# ibc-parse-config
Public repo to be able to propose changes to the configuration of IBC parser.

Please maintain the following structure:
- chain-id
- api link
- name in Cosmos Directory (the last part of the link):
  - testnets: https://testnet.cosmos.directory/archwaytestnet <= archwaytestnet
  - mainnets: https://cosmos.directory/archway <= archway
```json
{
  "Namada": 
    {
      "chain-id": "shielded-expedition.88f17d1d14",
      "api": "https://namada.api.liveraven.net",
      "cosmos-directory": ""
    },
  "Axelar Testnet": 
    {
      "chain-id": "axelar-testnet-lisbon-3",
      "api": "",
      "cosmos-directory": "axelartestnet"
    },
  ...
}
```
