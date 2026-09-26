<h1 align="center">Manuel Núñez</h1>

<p align="center">
  <b>Backend and AI Systems Engineer</b><br>
  Device to cloud to agent, end to end.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/manuel-agentic-ai"><img src="https://img.shields.io/badge/LinkedIn-manuel--agentic--ai-0A66C2?style=flat-square" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Remote-Honduras%20(UTC--6)-2EA44F?style=flat-square" alt="Remote from Honduras, UTC-6">
  <img src="https://img.shields.io/badge/Head%20of%20Engineering-SixSense%20Labs-24292F?style=flat-square" alt="Head of Engineering at SixSense Labs">
</p>

---

I build complete systems: firmware on the device, serverless backends on AWS, real-time APIs for mobile apps, and AI agents that operate those APIs. Remote since 2017, working with US and international teams.

## What I build

```mermaid
flowchart LR
    D["ESP32 devices<br/>C++ / FreeRTOS"] -- MQTT --> I["AWS IoT Core"]
    I --> L["AWS Lambda<br/>Python"]
    L --> S[("DynamoDB / S3")]
    L --> G["AppSync<br/>GraphQL"]
    G <--> M["iOS and Android apps"]
    A["AI agents<br/>Claude / MCP"] <--> G
```

## Highlights

- **Leadership:** lead an engineering team of about 20 across firmware, cloud, and web, and took a connected device from early prototypes to its first production batch.
- **Integration:** real-time bridge between AWS IoT Core and AppSync GraphQL subscriptions, so mobile apps monitor and control devices live.
- **Performance:** full-duplex binary UART protocol that cut a 2 MB firmware transfer between microcontrollers from 9 minutes to 45 seconds (12x).
- **AI agents:** an autonomous agent that operates a production GraphQL API as an ordinary Cognito user, with authorization kept in one place.

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square" alt="AWS Lambda">
  <img src="https://img.shields.io/badge/AWS%20IoT%20Core-FF9900?style=flat-square" alt="AWS IoT Core">
  <img src="https://img.shields.io/badge/AppSync-FF9900?style=flat-square" alt="AWS AppSync">
  <img src="https://img.shields.io/badge/DynamoDB-FF9900?style=flat-square" alt="DynamoDB">
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL">
  <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>
<p>
  <img src="https://img.shields.io/badge/Claude%20API-191919?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API">
  <img src="https://img.shields.io/badge/MCP-191919?style=flat-square" alt="Model Context Protocol">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/FreeRTOS-3E8E41?style=flat-square" alt="FreeRTOS">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

---

<sub>Most of my work lives in private repositories; the contribution graph below counts it.</sub>
