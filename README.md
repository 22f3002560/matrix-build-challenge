# Multi-Platform Matrix Build Challenge

[![Matrix Build](https://github.com/22f3002560/matrix-build-challenge/actions/workflows/matrix-build.yml/badge.svg)](https://github.com/22f3002560/matrix-build-challenge/actions/workflows/matrix-build.yml)

## 📧 Contact Information
**Email:** 22f3002560@ds.study.iitm.ac.in

## 🎯 Project Overview

This repository demonstrates a CI/CD pipeline using GitHub Actions with matrix build strategy for JavaScript/Node.js.

## 🔧 Matrix Configuration

**Build Type:** Node.js Versions  
**Variants:** 18, 20, 22  
**Total Jobs:** 3 parallel builds

## ✅ Validation Requirements

- [x] ✅ Matrix Strategy: 3 different variants
- [x] ✅ Parallel Execution: All jobs run simultaneously
- [x] ✅ Build Artifacts: Each job generates unique artifacts
- [x] ✅ Artifact Upload: Uses `actions/upload-artifact@v4`
- [x] ✅ Naming Convention: All artifacts prefixed with `build-557da5b-`
- [x] ✅ Step Identifier: Contains step with `matrix-557da5b`
- [x] ✅ Non-empty Artifacts: All artifacts contain actual content
- [x] ✅ README with Email: This file contains email address

## 📦 Generated Artifacts

Each build produces:
- `build-557da5b-18`
- `build-557da5b-20`
- `build-557da5b-22`

## 🚀 Quick Start

1. **Clone this repository**
```bash
git clone https://github.com/22f3002560/matrix-build-challenge.git
cd matrix-build-challenge
```

2. **View workflow results**
   - Go to [Actions tab](https://github.com/22f3002560/matrix-build-challenge/actions)
   - Click on the latest workflow run
   - Download artifacts to verify contents

## 📊 Workflow Details

- **Trigger:** Push to main/master, Pull Requests, Manual dispatch
- **Jobs:** 3 parallel matrix jobs + 1 verification job
- **Artifacts:** 3 build artifacts with 30-day retention
- **Verification:** Automatic validation of all artifacts

## 🛠️ Technologies Used

- GitHub Actions
- JavaScript/Node.js
- Matrix Build Strategy
- Artifact Management

## 📝 License

MIT License

---

**Generated with Matrix Build Workflow Generator**
**Build Date:** 11/9/2025
