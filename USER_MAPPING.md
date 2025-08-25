# User Mapping

| Container                      | UID:GID          | Notes                                         |
|--------------------------------|------------------|-----------------------------------------------|
| OAuth2 Proxy                   | 200000:200000    |                                               |
| Authentik                      | 200001:200001    |                                               |
| Synapse                        | 200002:200002    |                                               |
| Vaultwarden                    | 200003:200003    |                                               |
| ownCloud Infinite Scale        | 200004:200004    |                                               |
| Paperless-ngx                  | 200005:200005    | ⚠️ UID cannot be changed without rebuilding   |
| Gitea                          | 200006:200006    |                                               |
| OpenEMR                        | 200007:200007    |                                               |
| Statping-ng                    | 200008:200008    |                                               |
| Redis                          | 200009:200009    |                                               |
| Valkey                         | 200010:200010    |                                               |
| MariaDB/MariaDB UBI            | 200011:200011    |                                               |
| Postgres                       | 200012:200012    |                                               |
| Stirling-PDF                   | 200013:200013    |                                               |
| Matrix Authentication Service  | 200014:200014    |                                               |
| Certspotter                    | 200015:200015    |                                               |
| phpMyAdmin                     | 200016:200016    |                                               |
| NGINX Unprivileged             | 101:101          | Upstream default - will change in the future. |
| Element                        | 101:101          | Inherited from NGINX Unprivileged.            |
| acme.sh                        |                  | Privileged - upstream default.                |
| NGINX                          |                  | Privileged - upstream default.                |
| Nextcloud                      |                  | Privileged - upstream default.                |
| ntfy                           |                  | Privileged - upstream default.                |
| hardened_malloc                |                  | Not meant to be run - Alpine default.         |

