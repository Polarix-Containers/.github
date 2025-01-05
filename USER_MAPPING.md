# User Mapping

| Container                | UID:GID          | Notes                                         |
|--------------------------|------------------|-----------------------------------------------|
| OAuth2 Proxy             | 700000:700000    |                                               |
| Kanidm                   | 700001:700001    |                                               |
| Synapse                  | 700002:700002    |                                               |
| Vaultwarden              | 700003:700003    |                                               |
| ownCloud Infinite Scale  | 700004:700004    |                                               |
| Paperless-ngx            | 700005:700005    | ⚠️ UID cannot be changed by sysadmin           |
| Gitea                    | 700006:700006    |                                               |
| OpenEMR                  | 700007:700007    |                                               |
| Statping-ng              | 700008:700008    |                                               |
| Redis                    | 700009:700009    |                                               |
| Valkey                   | 700010:700010    |                                               |
| MariaDB/MariaDB UBI      | 700011:700011    |                                               |
| Postgres                 | 700012:700012    |                                               |
| NGINX Unprivileged       | 101:101          | Upstream default - will change in the future. |
| Element                  | 101:101          | Inherited from NGINX Unprivileged.            |
| acme.sh                  |                  | Privileged - upstream default.                |
| NGINX                    |                  | Privileged - upstream default.                |
| Nextcloud                |                  | Privileged - upstream default.                |
| hardened_malloc          |                  | Not meant to be run - Alpine default.         |

