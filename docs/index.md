# Get started

- [n8n / Pricing](https://n8n.io/pricing/)
- [n8nをローカル環境(Docker)でサクッと動かしてみよう！](https://zenn.dev/digilaweb/articles/d2918deeeb5c25)
  - 各種設定: 暗号化キー、タイムゾーン、ライセンスのアクティベーション

```shell
# deploy with npx
npx n8n
# ログインに失敗する場合に rm -rf ~/.n8n して初期化しているが適切化は不明

# deploy with docker
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

## Launch n8n with PostgreSQL on Docker

- [n8n](https://github.com/n8n-io/n8n)
- [Docker Installation / Using with PostgreSQL](https://docs.n8n.io/hosting/installation/docker/#using-with-postgresql)
- [n8n with PostgreSQL](https://github.com/n8n-io/n8n-hosting/tree/main/docker-compose/withPostgres)

```shell
git clone git@github.com:n8n-io/n8n-hosting.git
cd n8n-hosting/docker-compose/withPostgres
docker compose up
```

## MCP

- [n8n-MCP](https://github.com/czlonkowski/n8n-mcp)
- [【Claude Desktop × n8n-MCP】自然言語だけでAIエージェントを構築してみた](https://zenn.dev/tacoms/articles/c84240711aa3db)
- [Claude Codeでn8nワークフロー作るのが楽すぎて、もう手動で作る気が起きない件](https://zenn.dev/ryorn/articles/a6dc96dc425669)
- [ClaudeとMCPでn8nを対話的に構築する新しい方法を試してみた🔥](https://www.youtube.com/watch?v=6trwaTXyBkI)
- [This n8n mcp is INSANE... Let AI Create your Entire Automation](https://www.youtube.com/watch?v=xf2i6Acs1mI)

## Integration

- [Slack credentials / Using API access token](https://docs.n8n.io/integrations/builtin/credentials/slack/#using-api-access-token)
- [Google credentials](https://docs.n8n.io/integrations/builtin/credentials/google/)

# References

- [YouTube / n8n-io](https://www.youtube.com/@n8n-io/videos)
