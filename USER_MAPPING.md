# User Mapping

| Container                | UID:GID          | Notes                                         |
|--------------------------|------------------|-----------------------------------------------|
| Synapse                  | 700000:700000    |                                               |
| Vaultwarden              | 700001:700001    |                                               |
| Gitea                    | 700002:700002    |                                               |
| MariaDB/MariaDB UBI      | 700003:700003    |                                               |
| ownCloud Infinite Scale  | 700004:700004    |                                               |
| Kanidm                   | 700005:700005    |                                               |
| OpenEMR                  | 700006:700006    |                                               |
| Paperless-ngx            | 700007:700007    | ⚠️ UID cannot be changed by sysadmin           |
| Redis                    | 700008:700008    |                                               |
| Valkey                   | 700009:700009    |                                               |
| Statping-ng              | 700010:700010    |                                               |
| OAuth2 Proxy             | 700011:700011    |                                               |
| Postgres                 | 700012:700012    |                                               |
| NGINX Unprivileged       | 101:101          | Upstream default - will change in the future. |
| Element                  | 101:101          | Inherited from NGINX Unprivileged.            |
| acme.sh                  |                  | Privileged - upstream default.                |
| NGINX                    |                  | Privileged - upstream default.                |
| Nextcloud                |                  | Privileged - upstream default.                |
| hardened_malloc          |                  | Not meant to be run - Alpine default.         |

