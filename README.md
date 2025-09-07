# 智能招聘分析工具 🚀
# Intelligent Recruitment Analyzer

一个简单易用的招聘数据分析工具，支持Excel文件上传和智能分析。

A simple and user-friendly recruitment data analysis tool with Excel upload and intelligent analysis.

## 🌟 特色功能 Features

- 📤 **Excel文件上传** / Excel File Upload
- 📊 **多维度数据分析** / Multi-dimensional Data Analysis  
- 🌍 **地理分布分析** / Geographic Distribution Analysis
- 🏢 **行业背景分析** / Industry Background Analysis
- 📈 **可视化图表** / Visual Charts
- 📋 **详细分析报告** / Detailed Analysis Reports
- 💾 **PDF导出功能** / PDF Export Function
- 🌐 **中英文双语** / Bilingual Interface

## 🚀 快速开始 Quick Start

### 在线使用 Online Use
直接访问GitHub Pages链接即可使用。
Access the GitHub Pages link to use directly.

### 本地部署 Local Deployment
```bash
git clone https://github.com/YOUR_USERNAME/recruitment-analyzer.git
cd recruitment-analyzer
# 使用任何HTTP服务器运行，例如：
# Use any HTTP server, for example:
python -m http.server 8000
# 或者 or
npx serve .
```

## 📊 使用方法 How to Use

1. **上传文件** / Upload File
   - 点击上传区域选择Excel文件
   - 支持 .xlsx 和 .xls 格式

2. **查看分析** / View Analysis  
   - 系统自动生成多维度分析
   - 包含图表和详细报告

3. **导出报告** / Export Report
   - 点击"导出PDF"保存完整报告

## 📁 文件格式 File Format

Excel文件应包含以下字段：
Excel file should contain the following fields:

- Name (姓名)
- Score (评分)
- Location (地理位置)
- Company (当前公司)
- Career Summary (职业概述)
- Education (教育背景)

参考 `sample_data.xlsx` 文件获取示例数据格式。
Refer to `sample_data.xlsx` for sample data format.

## 🛠️ 技术栈 Tech Stack

- HTML5 + CSS3 + JavaScript
- Chart.js (图表库)
- SheetJS (Excel解析)
- jsPDF (PDF导出)

## 📄 许可证 License

MIT License

## 🤝 贡献 Contributing

欢迎提交Issue和Pull Request！
Issues and Pull Requests are welcome!

---

⭐ 如果这个项目对您有帮助，请给个星标！
⭐ If this project helps you, please give it a star!
