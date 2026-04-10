# 模型观念素养测量指标体系专家调查问卷（Streamlit）

这是一个基于 Streamlit 编写的单页问卷应用，对应“模型观念”素养测量指标体系构建的德尔菲法第一轮专家咨询问卷。

## 项目结构

- `app.py`：问卷主程序
- `requirements.txt`：依赖文件
- `README.md`：说明文档

## 本地运行

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 上传到 GitHub

1. 新建一个 GitHub 仓库。
2. 将这 3 个文件上传到仓库根目录。
3. 提交并推送。

## 部署到 Streamlit Community Cloud

1. 登录 Streamlit Community Cloud。
2. 连接 GitHub。
3. 选择你的仓库。
4. Main file path 填 `app.py`。
5. 点击 Deploy。

## 当前版本说明

- 单页问卷
- 支持整表一次性提交
- 支持页面内预览提交结果
- 支持下载 JSON 结果

## 后续可扩展

- 保存到 CSV / Excel
- 写入 Google Sheets
- 写入 Supabase / MySQL / PostgreSQL
- 增加登录口令或访问控制
