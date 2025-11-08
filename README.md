n8n-action
==========
[AI Workflow Automation Platform & Tools - n8n](https://n8n.io)

### Docker command [http://localhost:5678](http://localhost:5678)
```
docker run -it --rm  --name n8n -p 5678:5678 -e N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=true  -e N8N_RUNNERS_ENABLED=true -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n start --tunnel
```

### DevTunnel
- See [dirkarnez/devtunnel-playground](https://github.com/dirkarnez/devtunnel-playground)

### Web UI
- `https://${Tunnel ID}.devtunnels.ms:5678/`

### Notes
- `sudo chmod -R +x . && ./build.sh` in CI/CD .yaml file is good enough for running docker build on GitHub Action
- too busy - use Docker image instead
  - [Docker | n8n Docs](https://docs.n8n.io/hosting/installation/docker/#starting-n8n)
    - [n8nio/n8n - Docker Image | Docker Hub](https://hub.docker.com/r/n8nio/n8n)
      - [Docker | n8n Docs](https://docs.n8n.io/hosting/installation/docker/)
      - [如何在電腦安裝與部署 n8n（Docker） | Darren's Dev Blog](https://darrenjon.com/docs/n8n/n8n-docker-setup/)
      - [Windows從0開始安裝n8n (Docker)](https://vocus.cc/article/6875db50fd897800014b59e1)
      - [[Tool Note]  — 架設 n8n & 簡易使用指南 | RexHung's Blog](https://rexhung0302.github.io/2025/10/04/20251004/#more)
      - [AI的超自動化武裝【n8n】-安裝篇](https://www.cc.ntu.edu.tw/chinese/epaper/home/20250620_007304.html)
      - [【一鍵安裝 n8n】圖文教學，獲得無限額度自動化工具＆限時免費升級企業版功能](https://raymondhouch.com/lifehacker/digital-workflow/n8n-deploy-guide/)
      
