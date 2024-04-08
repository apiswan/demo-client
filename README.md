# demo-client
API swan demo client application

## Pre-requisite
1. [Goreplay](https://github.com/buger/goreplay)

## Official documentation
1. [API Swan](https://github.com/apiswan/documentation)

# Initialise gor with the following command
```
sudo ./gor --input-raw :8080 --input-raw-track-response --output-file swan-%d-%H-%M-%S.log
```

In addition to the client executable, you will need to create a `config.json` file to tailor the client's configuration to your specific needs. Here's an example configuration:

```json
{
    "encryption_key": "01234567890123456789012345678901",
    "replay_host_url": "http://localhost:8080",
    "client_id": "6513c8f4a5e88aec56f093dc",
    "client_port": "9080"
}
```
