# 掼蛋游戏项目

## 项目结构

```
Login+Battle/
├── backend/              # 后端项目
│   ├── src/
│   │   └── main/
│   │       ├── java/     # Java源代码
│   │       └── resources/ # 配置文件
│   ├── pom.xml          # Maven配置
│   └── README.md       # 后端说明文档
├── frontend/            # 前端项目
│   ├── src/
│   │   ├── api/       # API接口
│   │   ├── assets/    # 静态资源
│   │   ├── components/# 组件
│   │   ├── router/    # 路由配置
│   │   ├── utils/     # 工具函数
│   │   └── views/     # 页面组件
│   ├── dist/          # 构建输出
│   ├── package.json    # NPM配置
│   └── vite.config.js # Vite配置
├── 运行指南.md        # 项目运行指南
└── .gitignore        # Git忽略配置
```

## 技术栈

### 后端
- Spring Boot 3.1.5
- MyBatis Plus 3.5.4
- WebSocket
- MySQL

### 前端
- Vue 3
- Vite
- Element Plus
- Axios

## 快速开始

### 后端启动
```bash
cd backend
mvn spring-boot:run
```

### 前端启动
```bash
cd frontend
npm install
npm run dev
```

详细说明请参考 [运行指南.md](运行指南.md)
