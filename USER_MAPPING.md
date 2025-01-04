# User Mapping

| Container                | UID:GID          | Notes                                         |
|--------------------------|------------------|-----------------------------------------------|
| Synapse                  | 3000:3000        |                                               |
| Vaultwarden              | 3001:3001        |                                               |
| Gitea                    | 3002:3002        |                                               |
| MariaDB                  | 3003:3003        |                                               |
| ownCloud Infinite Scale  | 3004:3004        |                                               |
| Kanidm                   | 3005:3005        |                                               |
| OpenEMR                  | 3006:3006        |                                               |
| Paperless-ngx            | 3007:3007        | ⚠️ UID cannot be changed by sysadmin           |
| Redis                    | 3008:3008        |                                               |
| Valkey                   | 3009:3009        |                                               |
| Statping-ng              | 3010:3010        |                                               |
| OAuth2 Proxy             | 3011:3011        |                                               |
| Postgres                 | 70:70            | Upstream default - will change in the future. |
| NGINX Unprivileged       | 101:101          | Upstream default - will change in the future. |
| Element                  | 101:101          | Inherited from NGINX Unprivileged.            |
| MariaDB UBI              | 999:999          | Upstream default - will change in the future. |
| acme.sh                  |                  | Privileged - upstream default.                |
| NGINX                    |                  | Privileged - upstream default.                |
| Nextcloud                |                  | Privileged - upstream default.                |
| hardened_malloc          |                  | Not meant to be run - Alpine default.         |

