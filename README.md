# LiDZ DevOps
## 权限
### 组织权限系统
- General
  - Alter trace settings
  - Create new projects
  - Delete team project
  - Edit instance-level information
  - View instance-level information
  - Service Account
  - Make requests on behalf of others
  - Trigger events
  - View system synchronization information
- Boards
  - Administer process permissions
  - Create process
  - Delete field from organization
  - Delete process
  - Edit process
- Repos
  - Administer shelved changes
  - Administer workspaces
  - Create a workspace
- Pipelines
  - Administer build resource permissions
  - Manage build resources
  - Use build resources
  - View build resources
### 项目权限系统
- 分组
  - 新建分组
  - 删除分组
  - 添加用户
  - 权限设置
    - 总体
      - 项目
      - Edit project-level information
      - TODO: project properties
      - Rename team project
      - Suppress notifications for work item updates
      - Update project visibility
      - View project-level information
    - 主板
      - Change process of team project.
      - Create tag definition
      - Delete and restore work items
    - TODO: 做别的Test Plans
      - Create test runs
      - Delete test runs
      - Manage test configurations
      - Manage test environments
      - View test runs

### 仓库权限系统
- Bypass policies when completing pull requests
- Bypass policies when pushing
- Contribute
- Contribute to pull requests
- Create branch
- Create repository
- Delete repository
- Edit policies
  - max file size
  - max path length
  - path utf8?
  - path case sensitive
- Force push (rewrite history, delete branches and tags)
- Manage notes
- Manage permissions
- Read
- Remove others' locks
- Rename repository

## 功能
### Dash Board
- 普通Wiki(Md)
- 基于redoc的openAPI的APIwiki(Yml)
### Boards
- 通知功能
- 首屏
- TAG
  - 描述
- 需求 uuid?
  - 优先级
  - 描述
  - TAG
  - 指派人物(表列)
  - 子需求(表列)
  - 优先级
  - 状态
    - todo
    - doing (一旦改为这个 直接hook到下面的option工时)
    - done
    - failure
  - 关联(表列)
    - 其他需求
    - repo文件
    - 人员
  - 预期工时(optional)
- 迭代
  - 绑定(表列)
    - 需求
    - repo
    - 人员
    - CI
    - 测试
  - 日期事件(表列) 比如 2020/1/1 上线 , 2020/8/11 发售 ... 手动点击前往当前阶段,并汇报延期还是超前
  - 根据日期事件生成甘特图
  - 根据状态生成饼图
  - 迭代文档

### PipeLines
- TODO:天台过来完善
- pool parallel
- offline CI and upload
- 钩子
- openAPI test集成(test.yml) 可通过wiki生成

### 部署(加不加好?)

## 前端细节
### DashBoard
- 首屏Readme/Wiki
- 卡片系统
  - 日代码提交
  - 最新的issue
  - Project Stats
  - Member Stats
  - 迭代可视化选择