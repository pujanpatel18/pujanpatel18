# 🚀 GitHub Profile Repository Structure (`pujanpatel18/pujanpatel18`)

This repository contains the complete production-ready source files for **Pujan Patel** (`pujanpatel18`):

```text
pujanpatel18/
├── .github/
│   └── workflows/
│       └── snake.yml             # GitHub Actions workflow for contribution snake animation
├── README.md                     # Master GitHub Profile README
└── STRUCTURE.md                  # Project repository structure & deployment guide
```

---

## 🛠️ How to Deploy to GitHub

1. **Create Special Repository on GitHub**:
   - Repository Name: `pujanpatel18`
   - Description: *My personal GitHub profile README*
   - Public / Private: **Public**
   - Initialize with README: **No** (or overwrite)

2. **Push Files to Repository**:
   ```bash
   git init
   git add .
   git commit -m "feat: initial production-ready profile README and snake workflow"
   git branch -M main
   git remote add origin https://github.com/pujanpatel18/pujanpatel18.git
   git push -u origin main
   ```

3. **Enable GitHub Actions Permissions for Contribution Snake**:
   - Go to your repository **Settings** -> **Actions** -> **General**
   - Under **Workflow permissions**, select **Read and write permissions**
   - Click **Save**
   - Run the workflow manually from **Actions** tab -> **Generate Snake Contribution Grid** -> **Run workflow**
