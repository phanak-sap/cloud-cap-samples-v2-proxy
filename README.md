# CAP-example-v2proxy

Two standard CAP framework examples, modified to use V2-proxy 

prerequisites:
- NodeJs installed



**cap-sflight**

- cd cap-sflight
- npm install
- npm ci
- npm run start
- port is autogenerated, check console log, usually 4004 but can be different

service URLs:
- V2 - http://localhost:4004/v2/processor
- V2 metadata - http://localhost:4004/v2/processor/$metadata

- V4 - http://localhost:4004/processor
- v4 metadata - http://localhost:4004/processor/$metadata


**bookshop, from cloud-cap-samples**

- cd cloud-cap-samples
- npm install
- npm run bookshop
- port is autogenerated, check console log, usually 4004 but can be different

bookshop

- V2 - http://localhost:4004/v2/browse
- V2 metadata - http://localhost:4004/v2/browse/$metadata
