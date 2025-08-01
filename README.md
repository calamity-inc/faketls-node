## Initial deployment
```bash
git clone https://github.com/calamity-inc/faketls-node && cd faketls-node && docker compose pull && docker compose up -d
```
## Update existing deployment
```bash
git pull && docker compose pull && docker compose up -d
```
or:
```bash
cd faketls-node && git pull && docker compose pull && docker compose up -d
```
