# dreamlabs-findata-client
Dreamlabs Findata Client


## 

dreamlabs-findata/
├── dreamlabs-findata-server/                     # 后端目录
│   ├── requirements.txt        # Python 依赖
│   ├── main.py                # FastAPI 主程序
│   ├── database.py            # 数据库模型
│   └── auth.py                # 认证逻辑
├── dreamlabs-findata-client/                     # 前端目录
├── dreamlabs-findata-ui/                     # 前端目录
│   ├── package.json           # Node 依赖
│   ├── vite.config.js         # Vite 配置
│   ├── tailwind.config.js     # Tailwind 配置
│   └── src/
│       ├── main.jsx           # 入口文件
│       ├── App.jsx            # 路由主控
│       ├── api.js             # API 封装
│       ├── context/
│       │   └── AuthContext.jsx# 全局登录状态
│       ├── components/
│       │   ├── KlineChart.jsx # K线图组件
│       │   ├── DataTable.jsx  # 数据表格
│       │   └── ProtectedRoute.jsx # 路由守卫
│       └── pages/
│           ├── LandingPage.jsx      # 首页
│           ├── RegisterPage.jsx     # 注册页
│           ├── LoginPage.jsx        # 登录页
│           ├── DashboardPage.jsx    # 仪表盘
│           ├── ApiDebugger.jsx      # API调试
│           └── QueryPage.jsx        # 数据查询页面