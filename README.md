# Ory Oathkeeper Config
1. It will make call to Hydra with the bearer token supplied in the request
2. Hydra will return the client_id and a boolean indicating if the request is authentic or not
3. This client_id and resource is sent to Keto for authorization
4. Finally the request is forwarded to the upstream

![github oathkeeper](https://github.com/oyeprashar/keto-oathkeeper-config/assets/67927586/dcdf97ce-f976-46a0-b8e4-20b64be8ff7a)
