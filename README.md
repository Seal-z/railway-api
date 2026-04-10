# Railway API 部署项目

这是一个简单的 FastAPI 接口项目，用于部署到 Railway 平台。

## 文件说明

- `main.py` - 主程序，包含 API 路由
- `requirements.txt` - Python 依赖包
- `Procfile` - Railway 启动命令

## 本地测试

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

访问 http://localhost:8000 测试接口。

## 部署到 Railway

1. 将此项目推送到 GitHub
2. 在 Railway 中选择 "Deploy from GitHub repo"
3. 选择此仓库，自动部署
