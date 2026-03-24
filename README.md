# 薪资方案计算器

一个纯前端静态项目，提供多地区薪资方案的快速测算页面。

访问地址为：`https://kyleexu.github.io/cotton`

## 功能概览

- 中国大陆薪资计算器
- 香港薪资方案计算器
- 新加坡薪资方案计算器
- 美国薪资方案计算器

入口页：`index.html`

## 目录结构

```text
.
├── index.html
└── salary/
    ├── salary_calculator.html
    ├── hk_salary_calculator.html
    ├── sg_salary_calculator.html
    └── us_salary_calculator.html
```

## 本地运行

这是静态页面项目，不依赖后端服务。

方式一：直接双击打开 `index.html`。  
方式二：使用本地静态服务（推荐）。

例如使用 Python：

```bash
python3 -m http.server 8080
```

然后访问：`http://localhost:8080`

## 部署到 GitHub Pages

1. 将项目推送到 GitHub 仓库（例如 `cotton`）
2. 进入仓库 `Settings` -> `Pages`
3. `Source` 选择 `Deploy from a branch`
4. `Branch` 选择 `main`，目录选择 `/ (root)`
5. 保存后等待构建完成

## 说明

- 各页面计算结果用于快速估算，不构成税务或法律建议
- 税率、扣除项规则会随地区政策变化，请以官方最新规则为准

