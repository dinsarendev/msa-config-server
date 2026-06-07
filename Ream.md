1. MSA-CONFIG-SERVER
- Clone git@github.com:dinsarendev/msa-config-server.git
- Change Project Structure JKD21
- run on brower http://localhost:8085/api-gateway/dev
- Api-Gateway-> resource->api-gateway->api-gateway-dev.yaml
  - Change Database connection
    -   r2dbc:
          url: r2dbc:postgresql://localhost:2677/api_gateway_db
          username: postgres
          password: BBU@2026
2. API-GATEWAY
- Clone git@github.com:dinsarendev/api-gateway.git
- Change Project Structure JKD21
- Gradle -> Tasks-> application-> bootRun
3. Run Frontend on API-GATEWAY Project
- cd frontend
- npm install
- npm run dev
