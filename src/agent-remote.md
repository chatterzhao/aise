# 编码智能体：远程 AI 智能体

## 示例

### AutoDev

详细见：https://ide.unitmesh.cc/agent/custom-ai-agent.html

```json
[
  {
    "name": "内部 API 集成",
    "description": "在一个组织或项目中，不同系统或组件之间的通信接口。",
    "url": "http://127.0.0.1:8765/api/agent/api-market",
    "responseAction": "Direct"
  },
  {
    "name": "组件库查询",
    "description": "从组件库中检索特定的 UI 组件，以便在开发的应用程序中使用。",
    "url": "http://127.0.0.1:8765/api/agent/component-list",
    "responseAction": "TextChunk"
  },
  {
    "name": "页面生成",
    "description": "使用 React 框架，基于组件和状态来生成页面。",
    "url": "http://127.0.0.1:8765/api/agent/ux",
    "auth": {
      "type": "Bearer",
      "token": "eyJhbGci"
    },
    "responseAction": "WebView"
  },
  {
    "name": "DevInInsert",
    "description": "Update，並指定20秒的timeout時間",
    "url": "http://127.0.0.1:8765/api/agent/devins-sample",
    "responseAction": "DevIns",
    "defaultTimeout": 20
  }
]
```

### GitHub Copilot Extension

