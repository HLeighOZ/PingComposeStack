# PingComposeStack

## Repo Structure
```

├── docker-compose.yaml  # Key Compose file used to deploy solution
├── .env   # Global ENV VAR definitions
├── ping
│   ├── devops-crds.env  # Ping DEVOPS Credentials obtained from Registration email via [Ping Identity Devops Registration](https://developer.pingidentity.com/devops/how-to/devopsRegistration.html#)
├── profiles             # Local Product Profiles with Solution configurations   
│   ├── pingaccess
│   ├── pingdirectory
│   └── pingfederate
├── traefik
│   ├── acme.json
│   ├── cf_api_token.txt
│   ├── logs
│   └── traefik.yml
```    