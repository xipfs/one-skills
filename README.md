# one-skills

全栈开发 AI Agent Skills，包含 Vue3 管理后台、UniApp 移动端、Spring Boot、 MySQL 数据库设计规范。

## Skills 列表

### 前端开发

| Skill | 描述 | 技术栈 |
| --- | --- | --- |
| [`vue-admin`](https://skills.sh/xipfs/one-skills/vue-admin) | Vue3 管理后台开发规范 | Vue3 + Element Plus + TypeScript |
| [`uniapp`](https://skills.sh/xipfs/one-skills/uniapp) | UniApp 移动端开发规范 | UniApp + Vue3 + wot-design-uni |

### 后端开发

| Skill | 描述 | 技术栈 |
| --- | --- | --- |
| [`spring-boot`](https://skills.sh/xipfs/one-skills/spring-boot) | Java 后端开发规范 | Spring Boot + MyBatis-Plus |
| [`nodejs`](https://skills.sh/xipfs/one-skills/nodejs) | Node.js 后端开发规范 | NestJS + TypeORM |

### 数据库

| Skill | 描述 | 技术栈 |
| --- | --- | --- |
| [`mysql-design`](https://skills.sh/xipfs/one-skills/mysql-design) | MySQL 数据库设计规范 | MySQL 8 |

### 开发工具

| Skill | 描述 | 适用场景 |
| --- | --- | --- |
| [`git-version`](https://skills.sh/xipfs/one-skills/git-version) | Git 版本管理自动化规范 | Commit/Tag/Changelog/Release Notes |

## 安装

```bash
npx skills add xipfs/one-skills
```

## 使用方式

Skills 根据项目类型自动触发：

| 项目类型         | 触发 Skill     |
| ---------------- | -------------- |
| Vue3 管理后台    | `vue-admin`    |
| UniApp 移动端    | `uniapp`       |
| Java Spring Boot | `spring-boot`  |
| Node.js          | `nodejs`       |
| 数据库设计       | `mysql-design` |
| Git 版本管理     | `git-version`  |

## 每个 Skill 包含

- **技术栈版本** - 推荐的技术栈及版本
- **目录结构** - 标准的项目目录结构
- **命名规范** - 文件、类、方法、变量命名规则
- **RESTful API 规范** - 标准 CRUD 路径设计
- **响应格式** - 统一的 Result/PageResult 响应
- **实体/模型规范** - 基础实体、字段定义
- **认证规范** - JWT/Redis Token 认证
- **代码质量检查清单** - 开发完成检查项

## 发布到 skills.sh

1. 创建 GitHub 仓库 `xipfs/one-skills`
2. 推送代码到 main 分支
3. 访问 `https://skills.sh/xipfs/one-skills` 即可被索引

## 本地开发

```bash
# 克隆仓库
git clone https://github.com/xipfs/one-skills.git

# 目录结构
one-skills/
├── README.md
└── skills/
    ├── vue-admin/SKILL.md
    ├── uniapp/SKILL.md
    ├── spring-boot/SKILL.md
    ├── nodejs/SKILL.md
    ├── mysql-design/SKILL.md
    └── git-version/SKILL.md
```
