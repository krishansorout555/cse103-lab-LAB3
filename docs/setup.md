# Setup Guide

## Prerequisites

- Python 3.8 or higher
- Git 2.x or higher

## How to Run

```bash
git clone <repo-url>
cd my_first_repo
python3 src/main.py

Check that the file was created correctly:

```bash
cat docs/setup.md
cat > .gitignore << 'EOF'
# Python bytecode
__pycache__/
*.py[cod]
*.pyo

# Environment files
.env
.venv/
venv/
ENV/

# Build and distribution
dist/
build/
*.egg-info/
.eggs/

# IDE / Editor settings
.vscode/
.idea/
*.swp
*.swo

# Operating system files
.DS_Store
Thumbs.db

# Logs and temporary files
*.log
*.tmp
*.bak
