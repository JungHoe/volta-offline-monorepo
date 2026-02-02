# 🔌 Volta Offline Monorepo

> 폐쇄망 환경에서 Volta와 다중 Node.js 버전을 설치하는 실전 가이드

## 📋 Overview

기업 내부망처럼 인터넷 접속이 제한된 환경에서 Volta를 설치하고 
프로젝트별로 다른 Node.js 버전을 사용하는 방법을 단계별로 설명합니다.

### 테스트 환경
- **호스트 머신**: Node.js 25 (Volta 설치용)
- **프로젝트**: Node.js 14 / 20 / 22 (각 워크스페이스)

## 🎯 Use Case

- ✅ 내부망/폐쇄망 서버에 Volta 설치
- ✅ Nexus 같은 사내 Mirror Registry 사용
- ✅ USB/공유 드라이브를 통한 오프라인 배포
- ✅ 레거시 프로젝트와 신규 프로젝트 공존

## 📂 Structure

packages/
├── legacy-app/    # Node 14 + npm
├── stable-app/    # Node 20 + yarn
└── modern-app/    # Node 22 + pnpm

## 🚀 Quick Start

### 1. 온라인 환경 (준비 단계)
### 2. 오프라인 환경 (실제 설치)
### 3. 검증

## 📝 Step-by-Step Guide

[상세 설치 과정]

## 🔍 Troubleshooting

### Volta 바이너리 다운로드 실패
### Node 버전 전환 안 됨
### package.json volta 필드 무시됨

## 📚 References

- [Volta Official Docs](https://docs.volta.sh/)
- [Offline Installation Issue](https://github.com/volta-cli/volta/issues/...)
