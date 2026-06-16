# 区块链版权登记项目原型（结构重构版）

## 目录结构

```text
blockchain-prototype-restructured/
├── index.html
├── assets/
│   └── css/
│       └── style.css
├── pages/
│   ├── public/
│   │   ├── flow.html
│   │   ├── idcard-query.html
│   │   ├── cert-query.html
│   │   ├── results.html
│   │   ├── results-detail-registered.html
│   │   └── results-detail-certified.html
│   └── admin/
│       ├── flow.html
│       ├── login.html
│       ├── cert-records.html
│       ├── blockchain-cert.html
│       ├── cert-record-detail.html
│       ├── cert-excel-upload-modal.html
│       ├── cert-work-upload-modal.html
│       ├── reg-records.html
│       ├── new-registration.html
│       ├── reg-view.html
│       ├── reg-view-reviewing.html
│       ├── reg-view-completed.html
│       ├── reg-view-rejected.html
│       ├── reg-excel-upload-modal.html
│       └── reg-work-upload-modal.html
└── README.md
```

## 说明

- `index.html` 位于项目根目录，继续承担原型导航和左侧页面树功能。
- 左侧页面树中的每一个节点都已对应到一个独立 HTML 文件。
- 前端查询端页面位于 `pages/public/`。
- 后台管理端页面位于 `pages/admin/`。
- 原页面内嵌 CSS 已统一迁移到 `assets/css/style.css`。
- 页面交互脚本保留在各 HTML 中，以尽量保持原型现有交互不变。
